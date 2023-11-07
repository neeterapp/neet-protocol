---
description: Basic explanation of the Neet protocol structure and purpose.
---

# ℹ Neet Protocol Overview

### Users

Members of instances using the Neet protocol can be identified in 3 different ways:

{% tabs %}
{% tab title="Domain-linked users" %}
Domain-linked users are identified in the following way: `@domain.tld`. Users can be linked to a specific domain by creating a file in the domain's root folder with information linking them to their instance-specific username. More information on how to do that \[somewhere not finished].
{% endtab %}

{% tab title="Instance-linked users" %}
Instance-linked users are identified in the following way: `@username:domain.tld`. In this specific example, adding this user will result in adding the user `user` from the instance hosted at `domain.tld`. This is the default way all usernames work in the Neet Protocol.
{% endtab %}

{% tab title="Users on the client's instance" %}
_(Note: this might not work with all clients, as they decide to add it.)_\
Certain clients might allow you to add other people that are registered on the client's official instance by just using `@username`. Take into account that adding people this way will only work on that client and external users won't be able to add them if they don't know their instance-specific username (`@username:domain.tld`) or domain-linked username (`@domain.tld`).
{% endtab %}
{% endtabs %}

You can view more information about users at the Neet Protocol \[somewhere not finished too :)].

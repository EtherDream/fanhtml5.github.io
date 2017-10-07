---
layout: default
---

{% assign my_secret_string = "ShopifyIsAwesome!" | hmac_sha256: "secret_key" %}
My encoded string is: {{ my_secret_string }}

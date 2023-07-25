---
description: Route to '/winecellar/reserve'
---

# /reserve

POST:

{% swagger method="post" path="/winecellar/reserve" baseUrl="http://13.48.52.200:3000" summary="Reserve wine drink time" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="body" name="cellar_id" type="ObjectId" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="row" type="Number" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="col" type="Number" required="true" %}

{% endswagger-parameter %}
{% endswagger %}

---
description: Route to '/winecellar/'
---

# /

GET:

{% swagger method="get" path="/winecellar/" baseUrl="http://13.48.52.200:3000" summary="Initiate wine cellar -> create empty cellar and return cellar" %}
{% swagger-description %}

{% endswagger-description %}
{% endswagger %}

POST:

{% swagger method="post" path="/winecellar/" baseUrl="http://13.48.52.200:3000" summary="Drink wine from wine-cellar" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="body" name="cellarid" type="ObjectId" %}
id of wine-cellar
{% endswagger-parameter %}

{% swagger-parameter in="body" name="row" type="Number" %}
floor of wine to drink
{% endswagger-parameter %}

{% swagger-parameter in="body" name="col" type="Number" %}
th of wine to drink
{% endswagger-parameter %}
{% endswagger %}

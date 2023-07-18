---
description: Route to '/winecellar/cell/'
---

# /cell

GET:

{% swagger method="get" path="/winecellar/cell/" baseUrl="http://13.48.52.200:3000" summary="call to find where to put wine in the cellar -> algorithm" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="cellarid" type="ObjectId" required="true" %}
id of wine-cellar
{% endswagger-parameter %}

{% swagger-parameter in="query" name="wineid" type="ObjectId" required="true" %}
id of wine
{% endswagger-parameter %}
{% endswagger %}

POST:

{% swagger method="post" path="/winecellar/cell/" baseUrl="http://13.48.52.200:3000" summary="call to put wine in the cellar" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="body" name="cellarid" type="ObjectId" required="true" %}
id of wine-cellar
{% endswagger-parameter %}

{% swagger-parameter in="body" name="wineid" type="ObjectId" required="true" %}
id of wine
{% endswagger-parameter %}

{% swagger-parameter in="body" name="row" type="Number" required="true" %}
floor to put wine
{% endswagger-parameter %}

{% swagger-parameter in="body" name="col" type="Number" required="true" %}
th to put wine
{% endswagger-parameter %}
{% endswagger %}

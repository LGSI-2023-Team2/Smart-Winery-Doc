---
description: Route to '/winecellar/status/'
---

# /status

GET:

{% swagger method="get" path="/winecellar/status" baseUrl="http://13.48.52.200:3000" summary="return current status of wine cellar" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="id" type="ObjectId" %}
cellar id
{% endswagger-parameter %}
{% endswagger %}

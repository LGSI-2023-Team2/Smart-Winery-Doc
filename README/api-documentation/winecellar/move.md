---
description: Route to '/winecellar/move'
---

# /move

POST:

{% swagger method="post" path="/winecellar/move" baseUrl="http://13.48.52.200:3000" summary="Move wine1 to wine2 position" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="body" name="wine_id" type="ObejctId" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="wine1_row" type="Number" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="wine1_col" type="Number" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="wine2_row" type="Number" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="wine2_col" type="Number" required="true" %}

{% endswagger-parameter %}

{% swagger-parameter in="body" name="cellarid" type="ObejctId" required="true" %}

{% endswagger-parameter %}
{% endswagger %}

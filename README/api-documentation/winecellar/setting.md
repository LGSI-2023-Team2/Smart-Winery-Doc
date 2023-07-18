---
description: Route to '/winecellar/setting/'
---

# /setting

GET:

{% swagger method="get" path="/winecellar/setting/" baseUrl="http://13.48.52.200:3000" summary="call to get current setting of the wine-cellar" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" name="id" type="ObjectId" required="true" %}
id of wine-cellar
{% endswagger-parameter %}
{% endswagger %}

POST:

{% swagger method="post" path="/winecellar/setting/" baseUrl="http://13.48.52.200:3000" summary="call to set setting of the wine-cellar" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="body" name="cellarid" type="ObjectId" %}
id of wine-cellar
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor1_type" type="Number" %}
type of floor1
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor1_temperature_target" type="Number" %}
target temperature of floor1
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor1_is_smart_mode" type="Boolean" %}
smart mode of floor1
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor2_type" type="Number" %}
type of floor2
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor2_temperature_target" type="Number" %}
target temperature of floor2
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor2_is_smart_mode" type="Boolean" %}
smart mode of floor2
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor3_type" type="Number" %}
type of floor3
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor3_temperature_target" type="Number" %}
target temperature of floor3
{% endswagger-parameter %}

{% swagger-parameter in="body" name="floor3_is_smart_mode" type="Boolean" %}
smart mode of floor3
{% endswagger-parameter %}
{% endswagger %}

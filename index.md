---
layout: default
---
{% for recipe in site.recipes %}
* [{{ recipe.title }}]({{recipe.url | relative_url}})

{% endfor  %}

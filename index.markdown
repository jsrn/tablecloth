---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Tablecloth

## Baking

{% for recipe in site.baking %}
  <div><a href="{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Cocktails

{% for recipe in site.cocktails %}
  <div><a href="{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}
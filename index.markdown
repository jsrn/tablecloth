---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Tablecloth

## Techniques

{% for recipe in site.techniques %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Baking

{% for recipe in site.baking %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Beef

{% for recipe in site.beef %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Chicken

{% for recipe in site.chicken %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Fish

{% for recipe in site.fish %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Pork

{% for recipe in site.pork %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Soup

{% for recipe in site.soup %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Sauces

{% for recipe in site.sauces %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Vegetarian

{% for recipe in site.vegetarian %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Cocktails

{% for recipe in site.cocktails %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

## Drinks

{% for recipe in site.drinks %}

  <div><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.name }}</a></div>
{% endfor %}

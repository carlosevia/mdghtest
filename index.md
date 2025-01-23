---
title: Home
---

# Hello

{% for page in site.pages %}
{% unless page.path contains 'style.scss' %}
- [{{ page.title | default: page.name }}]({{ page.url | relative_url }})
{% endunless %}
{% endfor %}

Life is good

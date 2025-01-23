# Hello

{% for page in site.pages %}
- [{{ page.title | default: page.name }}]({{ page.url | relative_url }})
{% endfor %}

Life is good

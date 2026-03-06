{% for link in site.data.navigation.main %}
  {% if link.right %}
    <a class="normal right" href="{{ '/' | relative_url }}{{ link.url }}">{{ link.title }}</a>
  {% else %}
    <a class="normal" href="{{ '/' | relative_url }}{{ link.url }}">{{ link.title }}</a>
  {% endif %}
{% endfor %}

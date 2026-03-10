{% for link in site.data.navigation.main %}
  <a class="nav-link" href="{{ link.url | relative_url }}"{% if link.new_tab %} target="_blank" rel="noopener"{% endif %}>{{ link.title }}</a>
{% endfor %}

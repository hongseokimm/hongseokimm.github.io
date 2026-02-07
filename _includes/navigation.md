{% for link in site.data.navigation.main %}
  <a class="nav-link" href="{{ link.url | relative_url }}">{{ link.title }}</a>
{% endfor %}

{% assign current_path = page.url | replace: 'index.html', '' | replace: '.html', '' %}
{% for link in site.data.navigation.main %}
  <a class="nav-link" href="{{ link.url | relative_url }}"{% if current_path == link.url %} aria-current="page"{% endif %}{% if link.new_tab %} target="_blank" rel="noopener"{% endif %}>{{ link.title }}</a>
{% endfor %}

{% for link in site.data.navigation.main %}
  {% assign is_active = false %}
  {% assign link_url_with_slash = link.url | append: "/" %}
  {% assign link_url_with_html = link.url | append: ".html" %}
  {% if link.url == "/" and page.url == "/" %}
    {% assign is_active = true %}
  {% elsif page.url == link.url or page.url == link_url_with_slash or page.url == link_url_with_html %}
    {% assign is_active = true %}
  {% endif %}

  {% if link.url contains "http" %}
    {% assign resolved_url = link.url %}
  {% else %}
    {% assign resolved_url = link.url | relative_url %}
  {% endif %}

  <a class="nav-link{% if is_active %} is-active{% endif %}" href="{{ resolved_url }}"{% if link.new_tab %} target="_blank" rel="noopener"{% endif %}>{{ link.title }}</a>
{% endfor %}

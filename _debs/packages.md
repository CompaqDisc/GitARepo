---
---
{% for file in site.static_files %}
  <p>{{ file.path }} | {{ file.extname }}</p>
{% endfor %}

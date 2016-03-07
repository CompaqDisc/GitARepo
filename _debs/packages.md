---
permalink: /index.html
---
{% for file in site.static_files %}
  {{ file.path }} | {{ file.extname }}
{% endfor %}

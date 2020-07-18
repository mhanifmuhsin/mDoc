---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

  {% if page.custom_css %}
    {% for stylesheet in page.custom_css %}
    <link rel="stylesheet" href="{{ site.baseurl }}/assets/css/{{ stylesheet }}.css">
    {% endfor %}
  {% endif %}

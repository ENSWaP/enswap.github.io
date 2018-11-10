---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: archive
header:
    image: /assets/images/header.jpg
permalink: /
---

{% for post in site.posts limit: 3 %}
  {% include archive-single.html show_teaser="yes" %}
{% endfor %}


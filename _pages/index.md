---
layout: archive
header:
    image: /assets/images/header.jpg
permalink: /
---

{% include archive-single.html %}

{% for post in site.posts limit: 3 %}
  {% include archive-single.html show_teaser="yes" %}
{% endfor %}


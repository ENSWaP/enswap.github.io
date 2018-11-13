---
layout: archive
header:
    image: /assets/images/header.jpg
permalink: /
---

{% assign post = site.conferences | where:"title", 'ENSWaP Conference 2019' | first %}
{% include archive-single.html %}

{% for post in site.posts limit: 3 %}
  {% include archive-single.html show_teaser="yes" %}
{% endfor %}


---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-pubs.html %}
{% endfor %}

<hr>
## Pre-prints & working papers

{% for post in site.workingpapers reversed %}
  {% include archive-pubs.html %}
{% endfor %}

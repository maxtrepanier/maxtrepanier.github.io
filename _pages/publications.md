---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a> or on <a href="https://inspirehep.net/authors/1394490">my inspire profile</a>.</div>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

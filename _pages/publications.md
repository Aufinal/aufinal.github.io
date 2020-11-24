---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}

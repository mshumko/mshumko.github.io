---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Here is a list of all of my first-author and some of my co-author publications. Head on over to my [CV](/cv/) to see the complete list of publications.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

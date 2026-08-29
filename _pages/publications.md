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

Journal Articles
------
{% assign journal_pubs = site.publications | where: "type", "journal" | sort: "date" | reverse %}
{% for post in journal_pubs %}
  {% include archive-single.html %}
{% endfor %}

Conference Papers
------
{% assign conference_pubs = site.publications | where: "type", "conference" | sort: "date" | reverse %}
{% for post in conference_pubs %}
  {% include archive-single.html %}
{% endfor %}

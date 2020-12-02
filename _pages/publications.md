---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Journal Publication
---
{% include base_path %}

{% for post in site.publications_journal reversed %}
  {% include archive-single.html %}
{% endfor %}


Conference Paper
---

{% for post in site.publication_conference reversed %}
  {% include archive-single.html %}
{% endfor %}

Book Chapters
---

{% for post in site.publication_book reversed %}
  {% include archive-single.html %}
{% endfor %}

Theses
---
{% for post in site.publication_thesis reversed %}
  {% include archive-single.html %}
{% endfor %}
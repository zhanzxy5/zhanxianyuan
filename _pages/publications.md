---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A full list of my publications can also be find on my [Google Scholar profile](https://scholar.google.com/citations?user=pDMnGloAAAAJ).


Journal Publication
---
{% include base_path %}

{% for post in site.publications_journal reversed %}
  {% include archive-single.html %}
{% endfor %}


Conference Paper
---

{% for post in site.publications_conference reversed %}
  {% include archive-single.html %}
{% endfor %}

Book Chapters
---

{% for post in site.publications_book reversed %}
  {% include archive-single.html %}
{% endfor %}

Theses
---
{% for post in site.publications_thesis reversed %}
  {% include archive-single.html %}
{% endfor %}
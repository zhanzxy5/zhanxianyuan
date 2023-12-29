---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A full list of my publications can also be found on my [Google Scholar profile](https://scholar.google.com/citations?user=pDMnGloAAAAJ).


Preprints
---
{% include base_path %}

{% for post in site.publications_preprint reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

Conference Proceedings
---
{% include base_path %}

{% for post in site.publications_conference reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

Journal Publications
---

{% for post in site.publications_journal reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

Peer Reviewed Book Chapters
---

{% for post in site.publications_book reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

<!-- Theses
---
{% for post in site.publications_thesis reversed %}
  {% include archive-single.html %}
{% endfor %} -->
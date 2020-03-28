---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

---
title: "Image Reconstruction with Low-rankness and Self-consistency of k-space Data in Parallel MRI"
collection: publications
# permalink: /publication/2015-10-01-paper-title-number-3
# excerpt: ''
date: 2020-03-01
venue: 'Medical Image Analysis'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

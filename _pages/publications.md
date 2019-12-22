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
<span style="font-size:0.9em;text-align: justify">A full list of my publications can also be found on my <a href="https://scholar.google.com/citations?user=2yTeZ58AAAAJ&hl=en&oi=ao">Google Scholar</a> profile.</span>

### Journal Papers

<!-- <img style="float: left;" src="/images/cvpr.jpg" width="25%">  -->
<span style="font-size:0.9em;text-align: justify"> [1]  <b>TreeCaps: Tree-Structured Capsule Networks for Program Source Code Processing.</b><br />
  &nbsp; &nbsp; &nbsp; <span style="color:green">Vinoj Jayasundara</span>, Nghi Duy Quoc Bui, Lingxiao Jiang and David Lo <br />
 &nbsp; &nbsp; &nbsp; ML for Systems Workshop, Advances in Neural Information Processing Systems (<span style="color:green">NeurIPS</span>) 2019. <br/>
   &nbsp; &nbsp; &nbsp; <a href="https://arxiv.org/pdf/1910.12306.pdf">[Paper]</a> <a href="https://vinojjayasundara.github.io/files/NeurIPS19_ppt.pdf">[Presentation]</a> <a href="https://vinojjayasundara.github.io/files/NeurIPS19_Poster.pdf">[Poster]</a> <a href="https://github.com/vinojjayasundara/treecaps">[Code]</a></span>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## **Conference and Workshop Papers**

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## **Under Review**

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

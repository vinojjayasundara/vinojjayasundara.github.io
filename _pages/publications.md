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

## **Journal Papers**

* <img style="float: left;" src="/images/cvpr.jpg" width="25%"> </img> <div style="text-align: justify"><span style="font-size:0.9em;"> Jayasundara, Vinoj., Bui, N., Jiang, L. and Lo, D., TreeCaps: Tree-Structured Capsule Networks for Program Source Code Processing. Advances in Neural Information Processing Systems, ML for Systems Workshop (NeurIPS Workshops), 2019. </span></div>

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

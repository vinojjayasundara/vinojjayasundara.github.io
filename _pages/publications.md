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

<!-- <img style="float: left;" src="/images/cvpr.jpg" width="25%">  -->
<span style="font-size:0.9em;text-align: justify"> [1] <b>TreeCaps: Tree-Structured Capsule Networks for Program Source Code Processing.</b><br />
  <span style="color:green">Vinoj Jayasundara</span>, Nghi Duy Quoc Bui, Lingxiao Jiang and David Lo <br />
ML for Systems Workshop, Advances in Neural Information Processing Systems (<span style="color:green">NeurIPS</span>) 2019. <br/>
  <a href="https://arxiv.org/pdf/1910.12306.pdf">[Paper]</a></span>

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

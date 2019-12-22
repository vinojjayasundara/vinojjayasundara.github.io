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
<span style="font-size:0.9em;text-align: justify"> [1] Vinoj Jayasundara, Nghi Duy Quoc Bui, Lingxiao Jiang and David Lo<br />
TreeCaps: Tree-Structured Capsule Networks for Program Source Code Processing. <br />
ML for Systems Workshop, Advances in Neural Information Processing Systems (<span style="color:green">NeurIPS</span>) 2019.</span> <br/>
[Paper](https://arxiv.org/pdf/1910.12306.pdf)

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

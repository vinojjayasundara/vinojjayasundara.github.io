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

<img style="float: right;" src="/images/cvpr.jpg" width="10%"> Other text

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

---
layout: page
permalink: /apps/index.html
title: Apps
icon: icon-apple
tags: [mobile apps, development, apps]
modified: 2013-10-10
image:
  feature: apps.jpg
  credit: Alejandro Escamilla
  creditlink: http://alejandroescamilla.com/
products:
 - name: Apps4Contractor Daily Report
   link: http://apps4contractor.com
   image: a4c-sq.png

---

We do a lot when it comes to facilitating technology. You know that app you have been wanting to develop? The one after you bought the iOS book and said you would start as soon as you finished the book (just after you start the book). We want to to talk to you about that one.

## Apps we want to tell you about
<ul>{% for product in page.products %}
  <li>{{ product.name }}</li>{% endfor %}
</ul>

{% include a4c.html %}


## So Simple Theme is all about:

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
 - name: Coming Soon
   link: #
   image: Alpha_lowercase.png

---

We do a lot when it comes to facilitating technology. You know that app you have been wanting to develop? The one after you bought the iOS book and said you would start as soon as you finished the book (just after you start the book). We want to to talk to you about that one.

## Apps we want to tell you about
{% for product in page.products %}
<article class="entry" itemscope="" itemtype="http://schema.org/Blog" style="border-bottom-width:0;">
	<div class="work-content"> 
		<div class="project-wrap" itemprop="blogPost" itemscope="" itemtype="http://schema.org/BlogPosting">
			<a href="{{ product.link }}">
				<figure class="project-tease"> 
					<img src="{{ site.url }}/images/{{ product.image }}" alt="A4C teaser" border="0" itemprop="image"> 
					<figcaption> 
						<div class="figcaption-wrap"> 
							<h3 itemprop="name">{{ product.name }}</h3> 
						</div>
					</figcaption>
				</figure>
			</a>
		</div>
	</div>
</article>
{% endfor %}

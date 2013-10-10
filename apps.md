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
applications:
  -name: apps.jpg
   link: Alejandro Escamilla
   image: a4c-sq.png
---

We do a lot of stuff with technology. One of those things is facilitating mobile dreams coming true with the development that app you have been wanting developed...yes...that one.

## Apps we want to tell you about
{% for application in page.applications %}
<h1>{{ application.name }}</h1>
{% endif %} 

<article class="entry" itemscope="" itemtype="http://schema.org/Blog" style="border-bottom-width:0;">
	<div class="work-content"> 
		<div class="project-wrap" itemprop="blogPost" itemscope="" itemtype="http://schema.org/BlogPosting">
			<a href="http://apps4contractor.com">
				<figure class="project-tease"> 
					<img src="{{ site.url }}/images/a4c-sq.png" alt="A4C teaser" border="0" itemprop="image"> 
					<figcaption> 
						<div class="figcaption-wrap"> 
							<h3 itemprop="name">Apps4Contractor Daily Report</h3> 
						</div>
					</figcaption>
				</figure>
			</a>
		</div>
	</div>
</article>

## So Simple Theme is all about:

* Responsive templates. Looking good on mobile, tablet, and desktop.
* Gracefully degrading in older browsers. Compatible with Internet Explorer 9+ and all modern browsers.
* Minimal embellishments and subtle animations. 
* Readable typography to make your words shine.
* Support for large images to call out your favorite posts.
* Disqus comments if you choose to enable.
* Simple and clear permalink structure[^1].
* Tags for [Open Graph](https://developers.facebook.com/docs/opengraph/) and [Twitter Cards](https://dev.twitter.com/docs/cards) for a better social sharing experience.
* Vanilla [custom 404 page]({{ site.url }}/404.html) to get you started.
* Stylesheets for Pygments and Coderay [syntax highlighting](http://mmistakes.github.io/articles/so-simple-theme/code-highlighting-post/) to make your code examples look snazzy.
* Simple search that overlays results based on post title.
* [Grunt build script]({{ site.url }}/theme-setup/index.html#theme-development) for easier theme development.
* [Sitemap](https://github.com/mmistakes/so-simple-theme/blob/master/sitemap.xml) for search engines
---
layout: archive
title: "Past Events"
date: 
modified:
excerpt: ""
tags: []
image:
  feature:
  teaser:
---

<!--<figure>
	<a href="http://www.imagexd.org/2017/"><img src="{{ site.url }}/images/logo_eScience_2.png" style="width: 250px;"></a>
	<figcaption>ImageXD Workshop 2017</figcaption>
</figure>


<figure>
	<a href="http://www.imagexd.org/2016/"><img src="{{ site.url }}/images/logo_BIDS_2.png" style="width: 250px;" ></a>
	<figcaption>ImageXD Workshop 2017</figcaption>
</figure>-->


<div class="tiles">
{% for post in site.categories.workshops %}
	{% include post-grid.html %}
{% endfor %}	
</div><!-- /.tiles -->

<p>(TextXD 2016 and TextXD 2017 Spring still to be added.)</p>

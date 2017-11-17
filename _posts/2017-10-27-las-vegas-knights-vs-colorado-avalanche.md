---
layout: post
title: "Las Vegas Knights vs. Colorado Avalanche"
tags: eishockey
result: "7:0"
city: "Las Vegas, Nevada"
venue: "T-Mobile Arena"
img_folder: "/v1509484708/sports.5square.de/2017-10-27-las-vegas-knights-vs-colorado-avalanche/"
thumb: http://res.cloudinary.com/dqzz6rb2q/image/upload/a_exif/c_thumb,g_center,h_251,w_251/v1509484708/sports.5square.de/2017-10-27-las-vegas-knights-vs-colorado-avalanche/IMG_2734.jpg
---
{% for item in site.data.2017-10-27-las-vegas-knights-vs-colorado-avalanche %}
<div class="media">
  <a href="{{ site.img_baseurl }}{{ page.img_folder }}{{ item.file }}"><img src="{{ site.img_baseurl }}{{ site.img_thumb }}{{ page.img_folder }}{{ item.file }}" alt="{{ item.title }}" title="{{ item.title }}" /></a>
</div>
{% endfor %}

<div id="lightgallery">
{% for item in site.data.2017-10-27-las-vegas-knights-vs-colorado-avalanche %}
  <a href="{{ site.img_baseurl }}{{ page.img_folder }}{{ item.file }}" data-responsive="img/1-375.jpg 375, img/1-480.jpg 480">
      <img src="{{ site.img_baseurl }}{{ site.img_thumb }}{{ page.img_folder }}{{ item.file }}" alt="{{ item.title }}" />
  </a>
{% endfor %}
</div>

<div class="media">
  <a href="http://res.cloudinary.com/dqzz6rb2q/video/upload/br_300,vc_h264/v1509492132/IMG_2744_i1xq4x.mov"><img src="http://res.cloudinary.com/dqzz6rb2q/video/upload/br_300,c_thumb,h_251,vc_h264,w_251/v1509492132/IMG_2744_i1xq4x.jpg" alt="" title="This right here is a caption." /></a>
</div>

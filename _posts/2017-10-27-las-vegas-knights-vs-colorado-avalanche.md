---
layout: post
title: "Las Vegas Knights vs. Colorado Avalanche"
tags: eishockey
result: "7:0"
city: "Las Vegas, Nevada"
venue: "T-Mobile Arena"
img_folder: "/v1509484708/sports.5square.de/2017-10-27-las-vegas-knights-vs-colorado-avalanche/"
thumb: https://res.cloudinary.com/dqzz6rb2q/image/upload/a_exif/c_thumb,g_center,h_251,w_251/v1509484708/sports.5square.de/2017-10-27-las-vegas-knights-vs-colorado-avalanche/IMG_2734.jpg
---
<div id="lightgallery">
{% for item in site.data.2017-10-27-las-vegas-knights-vs-colorado-avalanche %}
  <a href="{{ site.img_baseurl }}{{ page.img_folder }}{{ item.file }}">
      <img src="{{ site.img_baseurl }}{{ site.img_thumb }}{{ page.img_folder }}{{ item.file }}" alt="{{ item.title }}" />
      <ul>
        <li>site.img_baseurl {{ site.img_baseurl }}</li>
         <li>page.img_folder {{ page.img_folder }}</li>
        <li>item.file {{ item.file }}</li>
    </ul>
  </a>
{% endfor %}
</div>

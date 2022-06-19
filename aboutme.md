---
layout: page
title: About me
---

My name is Shirin. I am a first year Ph.D. student in ESE department at Washington Univeristy in St. Louis. I am a group member at CIG LAB, advised by[ Professor Ulugbek Kamilov](https://cigroup.wustl.edu/ulugbek-s-kamilov/). I am interested in Computational Imaging, Medical Image Analysis, Inverse Problems and Deep Learning.  

I received  B.Sc. and M.S. degrees in Electrical Engineering, Communication major from Sharif University of Technology, Tehran, Iran, in 2017 and 2020. I started my Ph.D. in Washington University in St. Louis on January 2022. 

<p>&nbsp;</p>

<h1> News </h1>

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

<div style="display: none;">
  <h6>Page views:</h6>
  <a href="https://www.hitwebcounter.com" target="_blank">
  <img src="https://hitwebcounter.com/counter/counter.php?page=7680519&style=0007&nbdigits=5&type=page&initCount=0" title="Total Website Hits" Alt="Web Hits" border="0" /></a>
  <h6>Unique visitors</h6>
  <a href="https://www.hitwebcounter.com" target="_blank">
  <img src="https://hitwebcounter.com/counter/counter.php?page=7680520&style=0007&nbdigits=5&type=ip&initCount=0" title="Total Website Hits" Alt="Web Hits" border="0" /></a>
</div>

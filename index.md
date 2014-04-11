---
layout: default
section: home
title: Home
---

<img class="left" src="/images/NSF-logo.jpg" height=132 style="margin-right:20px;">
<img class="right" src="/images/TSU-logo.png" height=132 style="margin-left:20px;">

<h3>
<em style="color:maroon;">Characterization of Bio-Molecular Response to Environmental Stress</em>
</h3>
<br><br>
is a an HBCU Research Infrastructure in Science and Engineering (RISE) project funded by a 
National Science Foundation (NSF) award to Texas Southern University.

News:
====
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> ({{post.date | date_to_string}})
    </li>
  {% endfor %}
</ul>







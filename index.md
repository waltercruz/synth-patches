---
layout: page
title: Synth Patches Programming
tagline: 
---
{% include JB/setup %}

Ok, trying to use this thing. Just posting here some assorted synth-patches.

Mostly, things that I see requests on reddit synthreciptes and try to replicate.

<br />

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


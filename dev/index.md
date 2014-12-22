---
layout:         page
title:          Let's Create Together
---

We're creating a place that we can create and build together. Here's a working document that everyone can contribute to &mdash; whether it be ideas, neat tricks or guidelines. A brief <a href="{{ BASE_PATH }}/contribute">intro</a> of how you can contribute.

<!-- 
  <h3>Posts</h3>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
-->

{% for category in site.categories %} 
  <h2 id="{{ category[0] }}-ref">{{ category[0] | join: "/" }}</h2>
  <ul>
    {% assign pages_list = category[1] %}  
    {% include JB/pages_list %}
  </ul>
{% endfor %}

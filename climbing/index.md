---
layout: full-width
title: Climbing
---
# Climbing
{% fullwidth "assets/img/jm_shuksan.png" "Circumventing a yawning crevass atop of the Price Glacier." %}

I spend a good deal of my free time in pursuit of alpine climbing objectives. Here I recount some of my more noteable trips. My hope is that the information can be of some use to those looking to repeat the climbs. 

## Trip Reports
 <ul class="content-listing ">
    {% for post in site.posts %}
	{% if post.categories contains "climbing" %}
          <li class="listing">
            <hr class="slender">
            <a href="{{ post.url | prepend: site.baseurl }}"><h3 class="contrast">{{ post.title }}</h3></a>
            <br><span class="smaller">{{ post.date | date: "%B %-d, %Y" }}</span>  <br/>
            <div>{{ post.excerpt }}</div>
          </li>
	{% endif %}
    {% endfor %}
  </ul>


---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<section id="about">

I am Zhiheng Qian. I am a student at Shanghai Jiao Tong University. I will graduate in Spring 2027 and am applying for a PhD program start in Fall 2027.

My research interests lie in natural language processing and speech processing with a focus on automatic speech recognition.

</section>

<section id="publications">
## Publications

{% assign pubs = site.publications | sort: 'date' | reverse %}
{% if pubs.size > 0 %}
{% for pub in pubs %}
- [{{ pub.title }}]({{ pub.url | relative_url }}){% if pub.date %}, {{ pub.date | date: "%Y-%m-%d" }}{% endif %}
{% endfor %}
{% else %}
No publications yet.
{% endif %}

</section>

<section id="portfolio">
## Portfolio

{% assign works = site.portfolio | sort: 'date' | reverse %}
{% if works.size > 0 %}
{% for item in works %}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}
{% else %}
No portfolio items yet.
{% endif %}

</section>

<section id="blog">
## Blog Posts

{% assign posts = site.posts | where_exp: 'post', 'post.hidden != true' %}
{% if posts.size > 0 %}
{% for post in posts limit: 12 %}
- [{{ post.title }}]({{ post.url | relative_url }}){% if post.date %}, {{ post.date | date: "%Y-%m-%d" }}{% endif %}
{% endfor %}
{% else %}
No blog posts yet.
{% endif %}

</section>

<section id="cv">
## CV

- [View full CV]({{ '/cv/' | relative_url }})

</section>

<section id="guide">
## Guide

- [View markdown guide]({{ '/markdown/' | relative_url }})

</section>




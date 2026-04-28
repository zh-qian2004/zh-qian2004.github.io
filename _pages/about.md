---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am Zhiheng Qian, currently a student at Shanghai Jiao Tong University, expecting to graduate in Spring 2027. I am applying for PhD programs commencing in Fall 2027. My research interests center on natural language processing and speech processing, with a particular focus on MPP benchmarking of LMs, small-scale LMs, and automatic speech recognition.

## Publications
{: #publications}

{% assign pubs = site.publications | sort: 'date' | reverse %}
{% if pubs.size > 0 %}
{% for pub in pubs %}
- **[{{ pub.title }}]({{ pub.url | relative_url }})**{% if pub.paperurl %} \[[PDF]({{ pub.paperurl }})\]{% endif %}  
  {{ pub.authors }}. {{ pub.date | date: "%Y" }}. *{{ pub.venue }}.*
{% endfor %}
{% else %}
No publications yet.
{% endif %}

## Portfolio
{: #portfolio}

{% assign works = site.portfolio | sort: 'date' | reverse %}
{% if works.size > 0 %}
{% for item in works %}
- [{{ item.title }}]({{ item.url | relative_url }})
{% endfor %}
{% else %}
No portfolio items yet.
{% endif %}

## Blog Posts
{: #blog}

{% assign posts = site.posts | where_exp: 'post', 'post.hidden != true' %}
{% if posts.size > 0 %}
{% for post in posts limit: 12 %}
- [{{ post.title }}]({{ post.url | relative_url }}){% if post.date %}, {{ post.date | date: "%Y-%m-%d" }}{% endif %}
{% endfor %}
{% else %}
No blog posts yet.
{% endif %}

## CV
{: #cv}

- [View full CV]({{ '/cv/' | relative_url }})

## Guide
{: #guide}

- [View markdown guide]({{ '/markdown/' | relative_url }})

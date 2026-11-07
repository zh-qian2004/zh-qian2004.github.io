---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am Zhiheng Qian, currently a student at Shanghai Jiao Tong University and a member of the X-LANCE Lab, expecting to graduate in Spring 2027. I am applying for PhD programs commencing in Fall 2027. My research interests center on speech understanding and natural language processing. My current topics include automatic speech recognition (ASR), multilingual NLP, and LLM agents.

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

## CV
{: #cv}

- [View full CV]({{ '/cv/' | relative_url }})

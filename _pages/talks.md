---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

<h2>Conferences</h2>
{% for post in site.talks reversed %}
  {% if post.pubtype == 'Talk' %} 
    {% include archive-single-talk.html %}
  {% endif %}
{% endfor %}

<h2>Seminars</h2>
{% for post in site.talks reversed %}
  {% if post.pubtype == 'Seminar' %} 
    {% include archive-single-talk.html %}
  {% endif %}
{% endfor %}

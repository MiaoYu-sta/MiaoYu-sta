---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

<h3>Conferences</h3>
{% for post in site.talks reversed %}
    {% include archive-single-talk.html %}
{% endfor %}

<h3>Seminars</h3>
{% for post in site.talks reversed %}
  {% if post.pubtype == 'Seminar' %} 
    {% include archive-single-talk.html %}
  {% endif %}
{% endfor %}

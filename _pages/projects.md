---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
---

<h2>Projects</h2>
  {% for post in site.projects reversed %} 
    {% if post.pubtype == 'projects' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %}

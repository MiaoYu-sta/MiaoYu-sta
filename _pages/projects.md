---
layout: archive
permalink: /projects/
title: "Publications"
author_profile: true
---

<h2>Projects</h2>
  {% for post in site.projects reversed %} 
    {% if post.pubtype == 'project' %} 
      {% include archive-single.html %} 
    {% endif %}
  {% endfor %}

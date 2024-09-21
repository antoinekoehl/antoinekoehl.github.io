---
layout: single
classes: wide
title: "Projects"
permalink: /projects/
author_profile: true
---

I have been fortunate to work on a number of interesting projects with some remarkable people.
There's a bit of a divide - my prior work was mostly exeperimental, while my current work is mostly computational.

Here's a flavor of some of the projects I've worked on:

<div class="container-fluid">
  {% assign sorted_projects = site.projects | sort: "date" | reverse %}
  {% if sorted_projects.size > 0 %}
    {% for project in sorted_projects %}
      {% include project.html project=project %}
      <hr>
    {% endfor %}
  {% else %}
    <p>No projects found.</p>
  {% endif %}
</div>
---
layout: page
title: Projects
permalink: /projects/
---

# My Projects

Here are some of the projects I've worked on. Each project showcases different skills and technologies.

<div class="projects-list">
  {% for project in site.projects %}
    <div class="project-item">
      <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
      <p>{{ project.description }}</p>
      {% if project.technologies %}
        <p><strong>Technologies:</strong> {{ project.technologies | join: ', ' }}</p>
      {% endif %}
    </div>
  {% endfor %}
</div>

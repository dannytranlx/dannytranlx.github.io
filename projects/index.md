---
layout: default
title: Projects · Danny Tran
background: projects.jpg
---

##Projects

Here are some projects I worked on :

<ul class="projects">
  {% for project in site.data.projects %}
  <li>
    <h3><a href="{{ project.url }}">{{ project.name }}</a></h3>
    {{ project.description | markdownify }}
  </li>
  {% endfor %}
</ul>

<hr>
### [More on GitHub »](https://github.com/dannytranlx)

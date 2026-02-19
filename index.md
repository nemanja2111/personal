---
layout: home
title: "Nemanja Filipovic – AI & ML Engineer"
author_profile: true
---

## Welcome

Hi, I'm Nemanja. This site shows my AI & ML projects and blog posts.

## My Projects

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url | relative_url }}) — {{ project.excerpt }}
{% endfor %}

---
layout: home
title: Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }} 🥑
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{: .note }
Homework 2 is now posted. As before, I've provided a LaTeX template through Overleaf; click the 🍃 emoji next to the homework to access it. Follow [these instructions](https://www.overleaf.com/learn/how-to/Copying_a_project#Making_a_copy_of_a_project) to make a copy of the template, and then add your solutions. Typing your solutions in LaTeX is optional, but it's good to learn how to do!

{{ site.staffersnobio }}

[Jump to the current week](#week-2){: .btn .btn-yellow} [Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } [Assignment Solutions](https://campuswire.com/c/GAA3B3FEA/feed/17){: .btn .btn-purple }

{% for module in site.modules %}
{{ module }}
{% endfor %}

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

{: .welcome } 
Please carefully read the [Syllabus](../syllabus) and join [Campuswire](https://campuswire.com/p/GAA3B3FEA) for announcements.

{: .note }
The first homework assignment is posted below. If you want to type up your answers, I've provided a LaTeX template through Overleaf; click the 🍃 emoji next to the homework to access it. Follow [these instructions](https://www.overleaf.com/learn/how-to/Copying_a_project#Making_a_copy_of_a_project) to make a copy of the template, and then add your solutions. 

{{ site.staffersnobio }}

<!-- [Assignment Solutions](https://campuswire.com/c/GF82D3B2E/feed/73){: .btn .btn-purple } -->

[Jump to the current week](#week-1){: .btn } [Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue }

{% for module in site.modules %}
{{ module }}
{% endfor %}

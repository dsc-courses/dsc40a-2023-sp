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
Homework 4 is now posted. To copy the Overleaf template, follow [these instructions](https://www.overleaf.com/learn/how-to/Copying_a_project#Making_a_copy_of_a_project). 

{{ site.staffersnobio }}

[Jump to the current week](#week-2){: .btn .btn-yellow} [Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } [Assignment Solutions](https://campuswire.com/c/GAA3B3FEA/feed/17){: .btn .btn-purple }

{% for module in site.modules %}
{{ module }}
{% endfor %}

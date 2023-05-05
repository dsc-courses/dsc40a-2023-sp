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
Check your [seating assignment 🪑](resources/exams/seating_midterm1.pdf) before coming to the midterm on Friday! You will be given this [reference sheet 📝](resources/exams/reference_1.pdf) but no calculators or other aids are allowed.

{{ site.staffersnobio }}

[Jump to the current week](#week-2){: .btn .btn-yellow} [Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } [Assignment Solutions](https://campuswire.com/c/GAA3B3FEA/feed/17){: .btn .btn-purple }

{% for module in site.modules %}
{{ module }}
{% endfor %}

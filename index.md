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
[🪑 Seating assignments](resources/exams/seating_midterm2.pdf) for Midterm 2 are now available.

{{ site.staffersnobio }}

[Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } [Assignment Solutions](https://campuswire.com/c/GAA3B3FEA/feed/17){: .btn .btn-purple }

{% for module in site.modules %}
{{ module }}
{% endfor %}

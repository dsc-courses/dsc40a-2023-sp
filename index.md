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
Under Week 9 below, you will find a practice exam for Midterm 2, taken from my Winter 2022 course. You should take this exam on your own before Wednesday's discussion section, as the discussion section will be dedicated to reviewing solutions. It is recommended that you treat this like a mock exam, which means using only allowed resources and timing yourself. Note that this exam is a 90-minute exam, but yours will be a 50-minute exam.

{{ site.staffersnobio }}

[Jump to the current week](#week-2){: .btn .btn-yellow} [Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue } [Assignment Solutions](https://campuswire.com/c/GAA3B3FEA/feed/17){: .btn .btn-purple }

{% for module in site.modules %}
{{ module }}
{% endfor %}

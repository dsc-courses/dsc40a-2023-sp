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

{: .success} Welcome! Please carefully read the [Syllabus](../syllabus) and join [Campuswire](https://campuswire.com/p/GAA3B3FEA) for announcements. I'll see you in class on Monday!

{{ site.staffersnobio }}

<!-- [Assignment Solutions](https://campuswire.com/c/GF82D3B2E/feed/73){: .btn .btn-purple } -->

[Jump to the current week](#week-1){: .btn } [Lecture Recordings](https://podcast.ucsd.edu/){: .btn .btn-blue }

{% for module in site.modules %}
{{ module }}
{% endfor %}

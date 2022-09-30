---
layout: home
title: Home + Schedule
permalink: index.html
seo:
  type: Course
  name: Rubik's Cube Decal
nav_order: 1
mathjax: true
---

# Rubik's Cube Decal

## Fall 2022

[Jump to latest week](#week-1)

---

## Announcements

{% assign announcement = site.announcements | reverse | first %}
{{ announcement }}

[All previous announcements can be found here](announcements.md)

---

## Important Links

- The syllabus [can be found here](syllabus.md)
- **Frequently Asked Questions**: Please read the class [FAQ page](faq.md)
- [bCourses link](https://bcourses.berkeley.edu/courses/1519879)

---

## Schedule

{% for module in site.modules %}
{{ module }}

---

{% endfor %}
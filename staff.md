---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

## Lead Facilitators

{% assign instructors = site.staffers | where: 'role', 'Lead Facilitator' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Facilitator' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Facilitators

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

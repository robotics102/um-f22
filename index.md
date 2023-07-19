---
title: Home
layout: home
nav_order: 1
---
# Introduction to AI and Programming
ROB 102, Fall 2022 at The University of Michigan
{: .fs-6 .fw-300 }

This is the course page for the Fall 2023 offering of [Robotics 102: Introduction to AI and Programming](https://robotics102.org) at the University of Michigan. This site contains information relevant to Michigan students.

# Instructors

<div class="staff-row">
{% assign instructors = site.staff | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

{% assign teaching_assistants = site.staff | where: 'role', 'Instructional Aide' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

# Instructional Aides

<div class="staff-row">
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
</div>
{% endif %}

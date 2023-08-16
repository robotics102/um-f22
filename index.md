---
title: Home
layout: home
nav_order: 1
---
# Introduction to AI and Programming
{: .no_toc }
ROB 102, Fall 2022 at the University of Michigan
{: .fs-6 .fw-300 }

This is the course page for the Fall 2023 offering of [Robotics 102: Introduction to AI and Programming](https://hellorob.org) at the University of Michigan. This site contains information relevant to Michigan students.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# Meeting Times

<i class="fa-solid fa-chalkboard-user"></i> **Lectures:** Tues & Thurs 3-4:30 PM @ FRB 1060

<i class="fa-solid fa-flask"></i> **Labs:**
* F 10:30 AM-12:30 PM @ FRB 1060
* F 12:30-2:30 PM @ FRB 1060
* F 2:30-4:30 PM @ FRB 1060

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

# Office Hours

The office hour schedule for Fall 2022 can be found below.
You must be logged in to your UM account in order to see the event details.
You can also access the calendar or add it to your calendar using [this link](https://calendar.google.com/calendar/u/1?cid=Y18waWZjdjFmbG8ycWpsdG0wN3UzMG8yOGtkOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t).

<iframe
    src="https://calendar.google.com/calendar/embed?src=c_0ifcv1flo2qjltm07u30o28kd8%40group.calendar.google.com&ctz=America%2FDetroit"
    style="border: 0" width="800" height="600" frameborder="0" scrolling="no">
</iframe>

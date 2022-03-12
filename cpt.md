---
layout: page
title: City of Cape Town
---

<!-- ### <ins>Apple/Outlook Calendar</ins>, [Google Calendar](cpt-google) -->


Find your [area number](https://www.capetown.gov.za/Loadshedding1/loadshedding/maps/Load_Shedding_All_Areas_Schedule_and_Map.pdf), then select your calendar app.

{% assign baseURL = "webcal://raw.githubusercontent.com/chrismailer/loadshedding-calendar/feed/city_of_cape_town/area_" %}
{% assign googleURL = "https://calendar.google.com/calendar/render?cid=" %}

{% for i in (1..16) %}
<!-- Area {{$i}} - [Apple]({{ baseURL | append: i | append: ".ics" }}) [Outlook]({{ baseURL | append: i | append: ".ics" }}) [Google]({{ googleURL | append: baseURL | append: i | append: ".ics" }}) -->
Area {{$i}} - [Add to Calendar]({{ baseURL | append: i | append: ".ics" }})
{% endfor %}

## Google Calendar
1. Copy the "Add to Calendar" link
2. On your computer, open [Google Calendar](https://calendar.google.com/)
3. On the left, next to "Other calendars", click the plus and then **From URL**.
4. Paste the "Add to Calendar" link here
5. Click Add calendar. The calendar appears on the left, under "Other calendars".
**NB**: Google calendar syncing can take up to 12 hours

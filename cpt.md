---
layout: page
title: City of Cape Town
---

<!-- ### <ins>Apple/Outlook Calendar</ins>, [Google Calendar](cpt-google) -->


Find your [area number](https://www.capetown.gov.za/Loadshedding1/loadshedding/maps/Load_Shedding_All_Areas_Schedule_and_Map.pdf), then select your calendar app.
**NB**: Google calendar syncing can take up to 24 hours

{% assign baseURL = "webcal://raw.githubusercontent.com/chrismailer/loadshedding-calendar/feed/city_of_cape_town/area_" %}
{% assign googleURL = "https://calendar.google.com/calendar/render?cid=" %}

{% for i in (1..16) %}
Area {{$i}} - [Apple]({{ baseURL | append: i | append: ".ics" }}) [Outlook]({{ baseURL | append: i | append: ".ics" }}) [Google]({{ googleURL | append: baseURL | append: i | append: ".ics" }})
{% endfor %}

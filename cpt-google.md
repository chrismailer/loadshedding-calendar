---
layout: page
title: City of Cape Town
---

[Apple/Outlook Calendar](cpt), <ins>Google Calendar</ins>


Find your area number on the [map](https://www.capetown.gov.za/Loadshedding1/loadshedding/maps/Load_Shedding_All_Areas_Schedule_and_Map.pdf).

{% assign baseURL = "webcal://raw.githubusercontent.com/chrismailer/loadshedding-calendar/feed/city_of_cape_town/area_" %}
{% assign googleURL = "https://calendar.google.com/calendar/u/0/r?cid=" %}

{% for i in (1..16) %}
Area {{$i}} - [Subscribe]({{ googleURL | append: baseURL | append: i | append: ".ics" }})
{% endfor %}

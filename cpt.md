---
layout: page
title: City of Cape Town
---

<ins>Apple/Outlook Calendar</ins>, [Google Calendar](cpt-google)


Find your area number on the [map](https://www.capetown.gov.za/Loadshedding1/loadshedding/maps/Load_Shedding_All_Areas_Schedule_and_Map.pdf).

{% assign baseURL = "webcal://raw.githubusercontent.com/chrismailer/loadshedding-calendar/feed/city_of_cape_town/area_" %}

{% for i in (1..16) %}
Area {{$i}} - [Subscribe]({{ baseURL | append: i | append: ".ics" }})
{% endfor %}


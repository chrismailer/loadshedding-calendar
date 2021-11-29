---
layout: page
title: City of Cape Town
---

Find your area number on the [map](https://www.capetown.gov.za/Loadshedding1/loadshedding/maps/Load_Shedding_All_Areas_Schedule_and_Map.pdf).

{% assign baseURL = "webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_" %}
{% assign googleURL = "https://calendar.google.com/calendar/u/0/r?cid=" %}

{% for i in (1..17) %}
Area {{$i}} - [Add calendar]({{ baseURL | append: i | append: ".ics" }}), [Google Calendar]({{ googleURL | append baseURL | append: i | append: ".ics" }})
{% endfor %}


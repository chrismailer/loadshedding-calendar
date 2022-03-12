---
layout: page
title: City of Cape Town
---

<!-- ### <ins>Apple/Outlook Calendar</ins>, [Google Calendar](cpt-google) -->

Find your area number [here](https://www.capetown.gov.za/Loadshedding1/loadshedding/maps/Load_Shedding_All_Areas_Schedule_and_Map.pdf)

{% assign baseURL = "webcal://raw.githubusercontent.com/chrismailer/loadshedding-calendar/feed/city_of_cape_town/area_" %}
{% assign googleURL = "https://calendar.google.com/calendar/render?cid=" %}

{% for i in (1..16) %}
<!-- Area {{$i}} - [Apple]({{ baseURL | append: i | append: ".ics" }}) [Outlook]({{ baseURL | append: i | append: ".ics" }}) [Google]({{ googleURL | append: baseURL | append: i | append: ".ics" }}) -->
Area {{$i}} - [Add to Calendar]({{ baseURL | append: i | append: ".ics" }})
{% endfor %}

## Google Calendar
1. Copy the "Add to Calendar" link for the area you'd like to add
2. Paste the "Add to Calendar" link [here](https://calendar.google.com/calendar/u/0/r/settings/addbyurl)
3. Click Add calendar
**NB**: Google calendar syncing can take up to 12 hours

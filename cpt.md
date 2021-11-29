---
layout: page
title: City of Cape Town
---

Find your area number on the [map](https://www.capetown.gov.za/Loadshedding1/loadshedding/maps/Load_Shedding_All_Areas_Schedule_and_Map.pdf).

Area 1 - [Add Calendar](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_1.ics),
[Google Calendar](https://calendar.google.com/calendar/u/0/r?cid=webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_1.ics)

[Area 2](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_2.ics)

[Area 3](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_3.ics)

[Area 4](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_4.ics)

[Area 5](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_5.ics)

[Area 6](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_6.ics)

[Area 7](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_7.ics)

[Area 8](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_8.ics)

[Area 9](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_9.ics)

[Area 10](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_10.ics)

[Area 11](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_11.ics)

[Area 12](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_12.ics)

[Area 13](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_13.ics)

[Area 14](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_14.ics)

[Area 15](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_15.ics)

[Area 16](webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_16.ics)

{% assign baseURL = "webcal://raw.githubusercontent.com/chrismailer/loadshedding/main/western_cape/city_of_cape_town/area_" %}

{% for i in (1..17) %}
Area {{$i}} - [Add calendar]({{ baseURL | append: i | append: ".ics" }})
{% endfor %}


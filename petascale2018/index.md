---
layout: info
title: About the meeting
year: workshop2018
---
          {% assign workshop_len = 345600 %}
{% assign info = site.data[page.year].dates %}
The *12th Scalable Tools Workshop*
(formerly the Petascale Tools Workshop and
CSCADS Workshop on Petascale Tools)
will be held {{info.startdate | date: "%A, %B %-d"}} through {{info.startdate | date: "%s" | plus: workshop_len |  date: "%A, %B %-d"}} 
this year at the {{info.location}} in {{info.city}}, {{info.state}}.
As in previous years, we will begin with presentations of people's work,
and will then break up into working groups to tackle real technical problems
for the second half of the workshop.

Dinner on Sunday evening will be from 6:00 to 7:30pm.



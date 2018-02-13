---
layout: info
title: Location
year: 2018
---
Scalable Tools Workshop {{site.data.dates.year}} will be held at the
beautiful <a href="http://www.granlibakken.com">Granlibakken Resort</a> in Lake Tahoe,
California.
<p>
Workshop registration includes lodging and meals.
The Granlibakken will also arrange transportation between Reno Airport and the hotel.

<p>
Costs are as follows:

<p>

<table class="prices">
    <tr>
        <th bgcolor="lightblue">Room Type</th>
        <th bgcolor="lightblue">Full Workshop cost</th>
    </tr>
    {% for p in site.data.prices %}
    <tr>
        <td>{{p[0]}}</td><td>{{p[1]}}</td>
    </tr>

    {% endfor %}
</table>


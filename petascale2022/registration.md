---
layout: info
title: Registration
---
Scalable Tools Workshop 2022 will be held at the
beautiful <a href="http://www.granlibakken.com">Granlibakken Resort</a> in Lake Tahoe, 
California. [Registration](https://www.secure.granlibakken.net/conference/) will 
be handled directly by the resort (enter group code "TOOLS22") and includes lodging and meals.

If you need transportation between Reno Airport and the hotel, you must register directly
through [North Lake Tahoe Express](https://www.northlaketahoeexpress.com/).

<p>
Costs are as follows:

<p>
<table class="prices">
    <tr>
        <th bgcolor="lightblue">Room Type</th>
        <th bgcolor="lightblue">Cost (4 nights/daily)</th>
    </tr>
    {% for p in site.data[page.year].prices %}
    <tr>
        <td>{{p[0]}}</td><td>{{p[1]}}</td>
    </tr>

    {% endfor %}
</table>

</p>
</p>

<p>
Meals, lodging, and workshop attendance are covered by the registration fee.
If you are traveling with companions who are not attending the workshop,
their meals and lodging will cost an additional $84 per person per day.
If you are staying beyond the workshop dates, you will need to call Granlibakken
to make arrangements.
</p>

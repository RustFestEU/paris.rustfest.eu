---
layout: blue_page
permalink: /about/
title: About
---

RustFest is Europe’s Rust-dedicated conference. The next edition of RustFest will take place as a two-day event in Zurich, Switzerland.

We care about diversity and accessibility at this conference -- please take a look at our [Code of Conduct](/code-of-conduct/) and [Accessibility Statement](/accessibility/).


<section>
  <h2>Team</h2>
  <ul class="team">
    {% for entry in site.data.team %}
      {% assign member=entry[1] %}
      {% unless member.alumn %}
        <li>
          {% include team-member.html member=member %}
        </li>
      {% endunless %}
    {% endfor %}
  </ul>
</section>

<section>
  <h2>Alumni</h2>
  <ul class="team">
    {% for entry in site.data.team %}
      {% assign member=entry[1] %}
      {% if member.alumn %}
        <li>
          {% include team-member.html member=member %}
        </li>
      {% endif %}
    {% endfor %}
  </ul>
</section>

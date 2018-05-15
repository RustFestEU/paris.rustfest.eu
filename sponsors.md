---
layout: default
permalink: /sponsors/index.html
title: Sponsoring
---

{% assign platinum_sponsors = site.sponsors | where: "group", "sponsor" | where: "level", "platinum" %}
{% assign gold_sponsors = site.sponsors | where: "group", "sponsor" | where: "level", "gold" %}
{% assign silver_sponsors = site.sponsors | where: "group", "sponsor" | where: "level", "silver" %}
{% assign bronze_sponsors = site.sponsors | where: "group", "sponsor" | where: "level", "bronze" %}
{% assign partners = site.sponsors | where: "group", "partner" %}
{% assign venue = site.sponsors | where: "group", "venue" %}
{% assign media = site.sponsors | where: "group", "media" %}

<div class="popout sponsors">
  <section>
    <h1>Sponsors</h1>
    <hr />
    <p>
      RustFest wouldn't be possible without the generous support of these fine folks:
    </p>
      <ul class="primary">
        {% for sponsor in platinum_sponsors %}
          <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.slug}}.{% if sponsor.png %}png{% else %}svg{% endif %}" /></a></li>
          {% if sponsor.desc %}
          <li><p>{{sponsor.desc}}</p></li>
          {% endif %}
        {% endfor %}
        {% for sponsor in gold_sponsors %}
          <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.slug}}.{% if sponsor.png %}png{% else %}svg{% endif %}" /></a></li>
          {% if sponsor.desc %}
          <li><p>{{sponsor.desc}}</p></li>
          {% endif %}
        {% endfor %}
        {% for sponsor in silver_sponsors %}
          <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.slug}}.{% if sponsor.png %}png{% else %}svg{% endif %}" /></a></li>
          {% if sponsor.desc %}
          <li><p>{{sponsor.desc}}</p></li>
          {% endif %}
        {% endfor %}
        {% for sponsor in bronze_sponsors %}
          <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.slug}}.{% if sponsor.png %}png{% else %}svg{% endif %}" /></a></li>
          {% if sponsor.desc %}
          <li><p>{{sponsor.desc}}</p></li>
          {% endif %}
        {% endfor %}
      </ul>
  </section>

  <section>
    <h2>Partners</h2>
    <hr />
      <ul>
        {% for sponsor in partners %}
          <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.slug}}.{% if sponsor.png %}png{% else %}svg{% endif %}" /></a></li>
          {% if sponsor.desc %}
          <li><p>{{sponsor.desc}}</p></li>
          {% endif %}
        {% endfor %}
      </ul>
  </section>

  <section>
    <h2>Media Partner</h2>
    <hr />
      <ul>
        {% for sponsor in media %}
          <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.slug}}.{% if sponsor.png %}png{% else %}svg{% endif %}" /></a></li>
          {% if sponsor.desc %}
          <li><p>{{sponsor.desc}}</p></li>
          {% endif %}
        {% endfor %}
      </ul>
  </section>

  <section>
    <h2>Venues</h2>
    <hr />
      <ul>
        {% for sponsor in venue %}
          <li><a href="{{sponsor.link}}" title="{{sponsor.name}}"><img src="/assets/sponsors/{{sponsor.slug}}.{% if sponsor.png %}png{% else %}svg{% endif %}" /></a></li>
          {% if sponsor.desc %}
          <li><p>{{sponsor.desc}}</p></li>
          {% endif %}
        {% endfor %}
      </ul>
  </section>

</div>


<section class="whitewithwheel">
  <h2>Interested in sponsoring us?</h2>
  <br />
  <p>
    <a class="button" href="mailto:sponsors@rustfest.eu">
      Get in touch now
    </a>
    <a class="button" href="/sponsors/packages/">
      Sponsor packages
    </a>
  </p>
</section>

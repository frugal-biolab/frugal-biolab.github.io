---
layout: page
title: People
permalink: /people/
---
<style>
  .grid { display: grid; grid-template-columns: auto auto; }
</style>

<div class="grid">
  {% for person in site.people %}
  <div class="grid-item">
    <img src="{{ person.photo_url }}" style="max-width: 80%;"><br>
    {{ person.name }}<br>
    {{ person.affiliation }}<br><br>
  </div>
  {% endfor %}
</div>

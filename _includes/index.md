---
layout: main-layout.njk
title: "My Planetary Playing Cards"
---

Welcome to My Planetary Playing Cards Showcase

<div class="planet-cards">
  {% include "planet-card.njk" with { planetName: "Sun", astronomicalUnit: "Type: G2V" } %}
  {% include "planet-card.njk" with { planetName: "Mercury", astronomicalUnit: "0.39 AU" } %}
  {% include "planet-card.njk" with { planetName: "Venus", astronomicalUnit: "0.72 AU" } %}
  {% include "planet-card.njk" with { planetName: "Earth", astronomicalUnit: "1 AU" } %}
  {% include "planet-card.njk" with { planetName: "Mars", astronomicalUnit: "1.52 AU" } %}
  {% include "planet-card.njk" with { planetName: "Jupiter", astronomicalUnit: "5.20 AU" } %}
  {% include "planet-card.njk" with { planetName: "Saturn", astronomicalUnit: "9.58 AU" } %}
  {% include "planet-card.njk" with { planetName: "Uranus", astronomicalUnit: "19.22 AU" } %}
  {% include "planet-card.njk" with { planetName: "Neptune", astronomicalUnit: "30.05 AU" } %}
</div>

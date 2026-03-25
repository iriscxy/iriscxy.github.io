---
layout: default
title: Halo
permalink: /halo-lab/
---

<style>
.people-section { margin: 2.5rem 0; }
.people-title { font-size: 1.6rem; font-weight: 700; margin-bottom: 1rem; }
.people-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
  gap: 18px;
}
.person-card {
  border: 1px solid rgba(0,0,0,.08);
  border-radius: 14px;
  padding: 14px;
  text-align: center;
  background: #fff;
}
.person-photo {
  width: 120px;
  height: 120px;
  border-radius: 999px;
  object-fit: cover;
  border: 1px solid rgba(0,0,0,.08);
}
.person-name { margin: 10px 0 6px; font-weight: 700; }
.person-email { font-size: .92rem; opacity: .85; }
.person-links {
  margin-top: 8px;
  font-size: .92rem;
  display: flex;
  gap: 10px;
  justify-content: center;
  flex-wrap: wrap;
}
.person-links a {
  text-decoration: none;
  border-bottom: 1px solid rgba(0,0,0,.2);
}
</style>

{% assign groups = include.groups | split: "," %}

{% for g in groups %}
  {% assign key = g | strip %}
  {% assign members = site.data.people[key] %}

  {% if members and members.size > 0 %}
  <section class="people-section" id="{{ key }}">
    <div class="people-title">
      {% if key == "phd" %}PhD Students
      {% elsif key == "master" %}Master Students
      {% elsif key == "undergrad" %}Undergraduates
      {% elsif key == "staff" %}Staff
      {% elsif key == "alumni" %}Alumni
      {% else %}{{ key | capitalize }}
      {% endif %}
    </div>

    <div class="people-grid">
      {% for p in members %}
      <div class="person-card">
        <img class="person-photo" src="{{ p.photo | relative_url }}" alt="{{ p.name }}">
        <div class="person-name">{{ p.name }}</div>

        {% if p.email %}
        <div class="person-email">
          <a href="mailto:{{ p.email }}">{{ p.email }}</a>
        </div>
        {% endif %}

        <div class="person-links">
          {% if p.links.scholar %}<a href="{{ p.links.scholar }}" target="_blank">Scholar</a>{% endif %}
          {% if p.links.website %}<a href="{{ p.links.website }}" target="_blank">Website</a>{% endif %}
          {% if p.links.github %}<a href="{{ p.links.github }}" target="_blank">GitHub</a>{% endif %}
          {% if p.links.cv %}<a href="{{ p.links.cv | relative_url }}" target="_blank">CV</a>{% endif %}
          {% if p.links.twitter %}<a href="{{ p.links.twitter }}" target="_blank">X</a>{% endif %}
        </div>
      </div>
      {% endfor %}
    </div>
  </section>
  {% endif %}
{% endfor %}
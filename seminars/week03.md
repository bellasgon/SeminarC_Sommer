---
layout: default
title: Week 3
instructor_slides: "/assets/follien/3.pdf"
---

# Week 3

<div class="card">
  <h3>👤 Presenter</h3>
  <p>Student Name</p>
</div>

<div class="card">
  <h3>📖 Readings</h3>
  <p>Author (Year)</p>
</div>

{% if page.instructor_slides %}
<div class="card">
  <h3>🎓 Instructor Slides</h3>
  <a class="button" href="{{ page.instructor_slides | relative_url }}" target="_blank">
    Open slides →
  </a>
</div>
{% endif %}

<div class="card">
  <h3>📊 Student Slides</h3>
  <p>Available via Dropbox (restricted access)</p>
</div>

---
layout: landing
---
{% for main_section in site.main_sections %}
  <div class="landing-section" style="background: #{{ main_section.color }};">{{ main_section.content }}</div>
{% endfor %}

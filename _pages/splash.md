---
title: "CrabSO"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/crabso.png
excerpt: "Maryland Division B Science Olympiad Invitational"

tourna_registration:
  - title: "Registration"
    excerpt: "Sign up for the 2026 CrabSO Invitational."
    btn_label: "Tournament Registration"
    btn_class: "btn--primary"
    url: "https://scilympiad.com/crabso"

volunteering:
  - title: "In-Person Volunteering"
    excerpt: "Join us at Clarksville Middle School!"
    btn_label: "Volunteer In-Person"
    btn_class: "btn--info"
    url: "https://www.signupgenius.com/go/10C044CA5A72FA5FCC61-60778799-crabso"
  - title: "Satellite Volunteering"
    excerpt: "Support us remotely!"
    btn_label: "Volunteer Satellite"
    btn_class: "btn--info"
    url: "https://www.signupgenius.com/go/10C044CA5A72FA5FCC61-61647944-crabso"
---

<div style="text-align: center; margin-bottom: 2em;">
  <h1>Tournament Registration for 2026 is Closed, Thank You For Coming!</h1>
  <p style="font-size: 1.1em;">
    The <strong>2026 In-person CrabSO Invitational</strong> will be held on <strong>January 24th, 2026</strong> at Clarksville Middle School.
    <br>
    The <strong>2026 Satellite CrabSO Invitational</strong> will be held from <strong>January 24th</strong> to <strong>January 31st, 2026</strong>.
  </p>
</div>

{% include feature_row id="tourna_registration" type="center" %}

<div style="text-align: center; margin-top: 2em; margin-bottom: 1em;">
  <h2>Volunteering Opportunities (Closed) </h2>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 1em;">
  {% for item in page.volunteering %}
    <div style="flex: 1; min-width: 300px; max-width: 45%; text-align: center;">
      <h3>{{ item.title }}</h3>
      <p>{{ item.excerpt }}</p>
      <a href="{{ item.url }}" class="btn {{ item.btn_class }}">{{ item.btn_label }}</a>
    </div>
  {% endfor %}
</div>

<div style="text-align: center; padding: 20px; background-color: #f9f9f9; border-radius: 10px; margin-top: 30px;">
  <h3 style="margin-bottom: 0.5em;">Event Supervisor Applications</h3>
  <p>Applications are currently <strong>closed</strong>. Thank you for your interest!</p>
</div>

---
permalink: /archive/
title: "Archives"

layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/crabso.png
excerpt: "Archives of past CrabSO tests and competition material."

tests_folder_2026:
  - title: "In-person Tests & Keys"
    btn_label: "Google Drive Folder"
    btn_class: "btn--primary"
    url: "https://drive.google.com/drive/folders/1TgioVE2iAWgxnPkbjp3MtN3MmW99vQWp"
  - title: "Satellite Tests & Keys"
    btn_label: "Google Drive Folder"
    btn_class: "btn--primary"
    url: "https://drive.google.com/drive/folders/1gQhNhBe7xGWz4-QRMnDhsJ2TI-Dx3N3o"

tests_folder_2025:
  - title: "2025 Tests & Keys"
    btn_label: "Google Drive Folder"
    btn_class: "btn--primary"
    url: "https://drive.google.com/drive/folders/1VNxpHZoQ18YKLYKOq0fyxLdHUOxY5_oV?usp=sharing"
---

<div style="text-align: center; padding-top: 20px; padding-bottom: 10px;">
  <h2>2026 Archives</h2>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding-bottom: 20px;">
  {% for item in page.tests_folder_2026 %}
    <div style="width: 280px; text-align: center;">
      <h3>{{ item.title }}</h3>
      {% if item.excerpt %}<p>{{ item.excerpt }}</p>{% endif %}
      <a href="{{ item.url }}" class="btn {{ item.btn_class }}">{{ item.btn_label }}</a>
    </div>
  {% endfor %}
</div>

<div style="text-align: center; padding-top: 20px; padding-bottom: 10px;">
  <h2>2025 Archives</h2>
</div>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding-bottom: 20px;">
  {% for item in page.tests_folder_2025 %}
    <div style="width: 280px; text-align: center;">
      <h3>{{ item.title }}</h3>
      {% if item.excerpt %}<p>{{ item.excerpt }}</p>{% endif %}
      <a href="{{ item.url }}" class="btn {{ item.btn_class }}">{{ item.btn_label }}</a>
    </div>
  {% endfor %}
</div>

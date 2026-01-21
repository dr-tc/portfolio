---
title: "Single Layout"
layout: single
permalink: /pages/single/

skills:
  - name: "Unity"
    icon: "fab fa-fw fa-unity"
    badges: ["C#", "Game Dev"]
    text: "Built multiple prototypes and a published jam game."
    level: 75
  - name: "Unreal Engine"
    icon: "fab fa-fw fa-unreal-engine"
    badges: ["Blueprints", "C++"]
    text: "Comfortable with Blueprints and basic C++ workflows."
    level: 55
  - name: "Game Design"
    icon: "fas fa-fw fa-gamepad"
    badges: ["Systems", "Levels", "UI"]
    text: "Designed mechanics, levels, and player feedback loops."
    level: 80
---

This page uses the `single` layout. It adds a page title, meta area, and supports a sidebar.
Good for standard content pages like About or Project detail pages.
{% include skills skills=page.skills %}
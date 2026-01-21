---
title: "Components"
layout: default
permalink: /components/
gallery_gameplay:
  # Recommended: width "240px" to "320px" keeps a neat grid
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 1"
    title: "Core loop"
    caption: "Core loop"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 2"
    title: "Challenge"
    caption: "Challenge"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 3"
    title: "Power-ups"
    caption: "Power-ups"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 4"
    title: "Boss arena"
    caption: "Boss arena"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 5"
    title: "UI feedback"
    caption: "UI feedback"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Gameplay 6"
    title: "Final tweak"
    caption: "Final tweak"

gallery_gameart:
  # Recommended: width "240px" to "320px" keeps a neat grid
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Art 1"
    title: "Style pass"
    caption: "Style pass"
    text: "Color palette and lighting tests."
    width: "280px"
  - url: /assets/images/placeholder.png
    image_path: /assets/images/placeholder.png
    alt: "Art 2"
    title: "Final polish"
    caption: "Final polish"
    text: "Final art, lighting, and UI polish."
    width: "280px"
---

This page is a workspace for demonstrating available components. Add examples below.

##Use markdown to format text 
This is a short introduction paragraph that explains the project, the theme, and the main goal of the jam. It gives visitors quick context before they view the media.

{% include figure image_path="/assets/images/placeholder-2.png" alt="Game Jam screenshot" caption="An example of how to insert a single image" %}

Here is a second paragraph with more detail about the gameplay loop, tools used, and what the team learned during the jam. This text sits between the intro image and the gallery.

## Gameplay Gallery
{% include gallery id="gallery_gameplay" layout="third" %}
## Game Art Gallery
{% include gallery id="gallery_gameart" layout="third" %}

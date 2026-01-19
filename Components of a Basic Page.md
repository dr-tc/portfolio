# Components of a Basic Page

This repo uses Jekyll layouts and includes to build each page. A page is made from a few predictable parts:



Add stuff about the importance of indentation in YAML

## 1) Front Matter
Every page starts with a front matter block (between `---` lines). It tells Jekyll which layout to use and can add page settings.

Example:

```markdown
---
title: "My Project Page"
layout: single
permalink: /projects/my-game/
---
```

## 2) Layout
The layout is the page template. It wraps your content with site-wide structure like the header and footer.  
Common layouts in this repo include:
- `default` (standard page wrapper)
- `splash` (hero-style homepage)
- `single` (simple content page)

## 3) Includes (Reusable Components)
Includes are reusable parts that appear across many pages:
- `head.html` — metadata, CSS links
- `masthead.html` — top navigation bar
- `footer.html` — footer content

Includes keep the site consistent and reduce repeated code.

## 4) Content (Markdown body)
Below the front matter is the page content, written in Markdown. This is where your text, headings, images, and links go.

## 5) Assets (CSS + images)
Your pages load styling from `assets/css/main.scss` and use images stored in `assets/`.

## Putting it all together
- The **page file** supplies metadata (front matter) and content.
- A **layout** wraps the content in a full HTML page.
- **Includes** insert shared components like the header and footer.
- **Assets** provide styles and images.

This structure lets you focus on content while keeping a clean, consistent design.
# Portfolio Site Overview (GitHub Pages + Jekyll)

This repo is a starter portfolio site designed for games students. You will fork it, edit a few files, and publish your portfolio using GitHub Pages.

## What is GitHub Pages?
GitHub Pages is a free hosting service from GitHub. It builds your site from the files in your repo and serves it as a website.  
You edit files in GitHub, and GitHub Pages updates the live site.

## What is Jekyll?
Jekyll is the static site generator that GitHub Pages uses. It lets you:
- Write content in Markdown (`.md`) files.
- Reuse layout and components with includes.
- Keep your site structured and easy to update.

We are **not** running Ruby/Gem commands locally. GitHub Pages does the Jekyll build for us automatically.

## Key folders and files

- `_config.yml`  
  Main site settings (title, description, base URL, navigation, etc.).

- `_pages/`  
  Your main pages (e.g., homepage, about page). These are Markdown files.

- `_includes/`  
  Reusable pieces of the site (header, footer, nav). Think of these as components.

- `_layouts/`  
  Page templates that wrap your content (e.g., default layout or splash layout).

- `assets/`  
  Stylesheets, images, and other files used by the site.

- `_data/`  
  YAML data files (like navigation menus) used by layouts/includes.

## Typical student workflow
1. Fork the repo into your own GitHub account.
2. Edit `_config.yml` (site title, description, social links).
3. Edit or add pages in `_pages/`.
4. Add images to `assets/`.
5. Enable GitHub Pages in repo settings.
6. Check your live site URL.

## Markdown basics
You will write most content in Markdown:
- `#` for headings
- `**bold**` for bold text
- `![alt text](image-url)` for images
- `[link text](url)` for links

## Why this structure?
It separates content from layout and design.  
That makes the site easier to maintain and gives you a professional workflow you can reuse.

# WCCL Systems

A responsive, static marketing site for WCCL Systems, built with [Astro](https://astro.build/) and deployed with GitHub Pages.

## Local development

```sh
npm install
npm run dev
```

## Updating content

The page content, service cards, project cards, and image URLs live in `src/pages/index.astro`. Global colors, typography, spacing, and responsive styles live in `src/styles/global.css`.

The current photos and contact details are placeholders intended to be replaced before launch.

## Content management

Editors use the site’s `/admin/` page to update text, services, projects, contact details, and images. Decap CMS saves the content behind the scenes and the site redeploys automatically. Authentication is invite-only, so editors do not need repository access or to work in the GitHub interface.

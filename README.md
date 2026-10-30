# Emmanuel de Mazieres — Portfolio

A refined, minimal industrial design portfolio inspired by high-end studios such as LAYER (layerdesign.com/projects/).

**Logo / Name:** Emmanuel de Mazieres

## Design Direction

- Clean, spacious, typography-led layout
- Soft warm off-white background (#f7f6f3)
- High-contrast near-black text
- Project presentation inspired by LAYER’s projects page: clear project name + client/category
- Elegant typography (Manrope + Inter)
- Subtle hover effects and scroll fade-ins
- Fully responsive

## Sections

- **Hero** — Confident, short introduction
- **Selected Work** — Two-column grid of project tiles
- **About** — Bio and key details
- **Contact** — Direct email + links

## Editing the Site

Go to **https://demazieres.com/admin/** and sign in with a GitHub personal access token
(fine-grained, limited to this repository, with *Contents: Read and write*). From there you can:

- edit the home page, About and Contact text, and change fonts, heading weight and text sizes
  (**Home Page & About**, with fonts under its **Fonts & Sizes** group)
- edit each project's text and pictures, show or hide a project, and add new ones (**Projects**)
- drag projects into a new order with **Reorder**, and drag page sections to move pictures and text

Every save commits to `main`; GitHub Pages republishes in a minute or two.
Uploaded photos are resized to 2400px and saved as WebP automatically.

## File Structure

```
_config.yml          Jekyll settings (GitHub Pages builds the site)
_data/site.yml       Home page, About and Contact text, plus fonts and sizes (under style:)
_data/fonts.yml      Fonts offered in the portal (Google Fonts)
_projects/*.md       One file per project: details, pictures, page sections
_layouts/            Page templates (default + project)
admin/               Editing portal (Sveltia CMS) and its config.yml
css/styles.css       Styles — colors are CSS variables at the top
js/main.js           Mobile menu, header and footer year
images/              Project photography and video
```

---

A quiet, confident portfolio for an industrial designer.

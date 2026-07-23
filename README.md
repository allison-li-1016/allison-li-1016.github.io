# allisonli.github.io

Personal academic website, built with [Jekyll](https://jekyllrb.com/) and the
[Minimal Light](https://github.com/yaoyao-liu/minimal-light) theme (loaded as a
`remote_theme`, so there's no local theme code to maintain). GitHub Pages
builds and deploys it automatically on every push to `main`.

## Structure

- `_config.yml` — site title, affiliation, email, and social links (Scholar,
  CV, GitHub, LinkedIn, Twitter). Edit this first.
- `index.md` — homepage content: About Me, Research Interests, News. Pulls in
  the section includes below.
- `_includes/projects.md`, `publications.md`, `conferences.md`, `awards.md`,
  `media.md` — section templates rendered on the homepage. Shouldn't need
  editing unless you want to change formatting.
- `_data/publications.yml`, `conferences.yml`, `awards.yml`, `media.yml` —
  the actual content for those sections. Add/edit entries here.
- `_projects/` — one Markdown file per research project. Each becomes its own
  page (e.g. `_projects/project-one.md` → `/projects/project-one/`) and shows
  up as a clickable card on the homepage.
- `_layouts/homepage.html` — page shell (header, avatar, icons, footer).
  Overrides the theme's default so a custom stylesheet can be loaded.
- `_layouts/project.html` — layout used by files in `_projects/`.
- `assets/img/` — avatar, favicon, project thumbnails.
- `assets/img/projects/` — teaser images for individual project pages.
- `assets/files/cv.pdf` — your CV, linked from the sidebar icons.
- `assets/css/custom.css` — small stylesheet for the project card grid.

## Filling in your content

1. Replace `assets/img/avatar.png`, `assets/img/favicon.png`,
   `assets/img/favicon-dark.png`, and `assets/files/cv.pdf` with real files.
2. Edit `_config.yml` with your name, affiliation, and links.
3. Edit `index.md` (About Me / Research Interests / News).
4. Add real entries to the YAML files in `_data/`.
5. Add/edit files in `_projects/` for each project, with a matching image in
   `assets/img/projects/`.

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.

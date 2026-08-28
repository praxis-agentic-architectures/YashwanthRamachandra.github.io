# Yashwanth Ramachandra — academic and professional portfolio

This repository contains the source for a research-oriented portfolio focused on Healthcare AI, generative and agentic AI, multimodal learning, clinical decision support, and trustworthy AI systems.

The site uses GitHub Pages-compatible Jekyll, Markdown, YAML data, Liquid includes, and lightweight CSS. It intentionally distinguishes documented work from developing research interests and does not publish unsupported credentials or results.

## Local development

Requirements: Ruby and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`. To test the production build without serving it:

```bash
bundle exec jekyll build
```

## Repository structure

```text
.
├── _config.yml              # Site metadata and GitHub Pages settings
├── _data/                   # Navigation and project metadata
├── _includes/               # Header, footer, metadata, and project cards
├── _layouts/                # Shared page and home layouts
├── assets/                  # Styles and social preview image
├── docs/CONTENT_GUIDE.md    # Editorial and evidence standards
├── projects/                # Detailed project profiles
├── index.md                 # Home page
├── research.md              # Research vision, questions, and roadmap
├── projects.md              # Project index
├── writing.md               # Publications, reports, articles, and talks
├── experience.md            # Concise professional profile
├── about.md                 # Biography and contact
├── cv.md                    # Web CV
└── 404.md                   # Not-found page
```

## Updating content

### Add a project

1. Add card metadata to `_data/projects.yml`.
2. Create `projects/<slug>.md` with `permalink: /projects/<slug>/`.
3. Follow the structure in `docs/CONTENT_GUIDE.md`.
4. Do not estimate results or imply clinical validation that did not occur.

### Add a publication or talk

Update `writing.md` under the correct category. Include a stable citation or event link only when it is public and verified. Do not mix peer-reviewed publications with preprints, internal presentations, or technical articles.

### Update navigation

Edit `_data/navigation.yml`. Use root-relative paths; Jekyll's `relative_url` filter applies `baseurl` during rendering.

## Deployment

GitHub Pages builds Jekyll sites from the configured publishing branch. The `github-pages` dependency mirrors the supported plugin set; `jekyll-seo-tag` and `jekyll-sitemap` are enabled. The current `url` and `baseurl` reflect the repository's organization-owned project Pages path. Update both values if a custom domain or different repository owner is configured later.

Before publishing, replace the clearly marked owner TODOs in `about.md`, `experience.md`, and `cv.md` with verified details.

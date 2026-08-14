# Troy Wilson Sports Science

Source for [troywilsonsportsscience.github.io](https://troywilsonsportsscience.github.io), a GitHub Pages site for Troy Wilson's applied sports science services, case studies, writing, and resources.

## Stack

- Jekyll via the `github-pages` gem
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) remote theme
- SCSS customizations in `assets/css/main.scss`
- GitHub Pages hosting

## Local development

Install a supported Ruby version and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000>. To perform a production-style build without starting a server:

```bash
JEKYLL_ENV=production bundle exec jekyll build
```

On PowerShell, set the environment variable separately:

```powershell
$env:JEKYLL_ENV = "production"
bundle exec jekyll build
```

Generated files are written to `_site/`.

## Repository structure

- `_pages/` — standalone site pages
- `_posts/` — dated blog posts
- `_resources/` — downloadable resource collection
- `_data/` — navigation and other structured site data
- `_includes/` — intentional Minimal Mistakes overrides only
- `assets/css/` — site-specific SCSS
- `assets/images/` — site imagery
- `assets/downloads/` — downloadable files
- `_config.yml` — Jekyll, theme, collection, and site configuration

Site content and configuration are published from the `master` branch.

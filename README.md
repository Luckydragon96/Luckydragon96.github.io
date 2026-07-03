# Academic Homepage with Jekyll

This repository contains a GitHub Pages-compatible Jekyll academic homepage.

## Quick Start

1. Edit `_config.yml` with your name, affiliation, email, and profile links.
2. Replace `assets/img/profile-placeholder.svg` with your own profile photo.
3. Update the content in:
   - `index.md`
   - `publications.md`
   - `projects.md`
   - `teaching.md`
   - `cv.md`
4. Push the repository to GitHub as `username.github.io`.
5. In GitHub, open `Settings` > `Pages`, then publish from the `main` branch.

Your site will be available at:

```text
https://username.github.io
```

## Local Preview

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open:

```text
http://localhost:4000
```

## Notes

- The site uses plain Jekyll layouts and SCSS, so it works well with GitHub Pages.
- Replace placeholder publication links (`#`) with real URLs before publishing.
- Avoid putting private files, unpublished sensitive data, or personal documents in a public GitHub Pages repository.

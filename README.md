# David Bani-Harouni

Source for [davidbaniharouni.com](https://davidbaniharouni.com), an academic website built with [al-folio](https://github.com/alshedivat/al-folio) and hosted on GitHub Pages.

## Local preview

1. Start Docker Desktop.
2. Run `docker compose up -d`.
3. Open [http://localhost:8080](http://localhost:8080).
4. Stop the preview with `docker compose down`.

## Content

- Biography and homepage settings: `_pages/about.md`
- Publications: `_bibliography/papers.bib`
- Social and academic links: `_data/socials.yml`
- Profile image: `assets/img/prof_pic.jpg`
- CV: `assets/pdf/cv.pdf`

Changes pushed to `main` are built automatically and published from the generated `gh-pages` branch.

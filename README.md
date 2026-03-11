# Vedalva

Bilingual (PL/EN) Jekyll site with stories and songs from the world of Noricia.

## Local development

1. Install Ruby and Bundler.
2. Install dependencies:

```bash
bundle install
```

3. Run local server:

```bash
bundle exec jekyll serve --watch
```

4. Open:

```text
http://localhost:4000
```

## Project structure

- `_posts/` - story and song entries in Polish and English
- `_layouts/` - page and post layouts
- `_includes/` - shared head/header/footer partials
- `_sass/` and `css/main.scss` - styles
- `index.html` and `start.html` - language entry pages
- `sitemaps.xml` and `robots.txt` - SEO files

## Content model

Multilingual pages/posts are paired by shared `ref` in front matter and a `lang` code (`pl` / `en`).

## License

MIT. See [LICENSE](/LICENSE).

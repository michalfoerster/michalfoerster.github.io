# Vedalva

Bilingual (Polish/English) author website of **Michał Foerster**, presenting the literary project **Ostatni Potop** and materials connected with the fictional world of **Norycja**.

Live site: <https://michalfoerster.github.io/>

## Local development

1. Install Ruby and Bundler.
2. Install dependencies:

```bash
bundle install
```

3. Run the local server:

```bash
bundle exec jekyll serve --watch
```

4. Open:

```text
http://localhost:4000
```

## Project structure

- `_posts/` — literary texts, stories, songs and other entries in Polish and English;
- `_layouts/` — page and post layouts;
- `_includes/` — shared page elements;
- `_sass/` and `css/` — styles;
- `assets/` — images, fonts and other media used by the website;
- `_data/` — structured website data;
- `index.html` and `start.html` — language entry pages;
- `sitemaps.xml` and `robots.txt` — SEO-related files.

Multilingual pages and posts may be paired using a shared `ref` value and a `lang` code (`pl` or `en`) in their front matter.

## Licensing

This repository contains two different categories of material governed by different terms.

### Website code

The software source code and technical implementation of the website are available under the terms stated in [`LICENSE`](./LICENSE), subject to all notices and attributions contained in that file.

This includes, where applicable:

- HTML and Liquid templates;
- CSS and Sass styles;
- scripts;
- Jekyll configuration and technical build files;
- modifications to the website theme made by the repository owner.

The website is based on the Jekyll Klisé theme and may contain code originating from third-party projects. Such code remains subject to its original licence and attribution requirements.

### Creative content

The literary and creative materials published in this repository are **not licensed under the MIT License**.

Unless a particular file explicitly states otherwise, all rights to original content authored by Michał Foerster are reserved. This includes, in particular:

- stories, poems, songs and other literary texts;
- descriptions of the fictional world, characters, cultures and history;
- original fictional-language materials;
- original illustrations, maps, graphics, photographs and recordings;
- Polish and English versions or translations created by the author;
- editorial selections, arrangements and compilations of original material.

Detailed terms are provided in [`CONTENT-LICENSE.md`](./CONTENT-LICENSE.md).

Third-party quotations, images, fonts, software and other materials remain subject to the rights and licences of their respective owners.

## Contact

Requests concerning quotation, republication, translation, adaptation, commercial use or other permissions should be addressed directly to Michał Foerster through the contact information published on the website.

---

# Vedalva — informacje po polsku

Dwujęzyczna strona autorska **Michała Foerstera**, poświęcona projektowi literackiemu **Ostatni Potop** oraz materiałom związanym z fikcyjnym światem **Norycji**.

## Licencje

Repozytorium zawiera dwa rodzaje materiałów, objęte odmiennymi zasadami.

### Kod strony

Kod źródłowy i techniczna implementacja strony są udostępnione na warunkach określonych w pliku [`LICENSE`](./LICENSE), z zachowaniem zawartych w nim informacji o autorach i wymaganych oznaczeń.

Dotyczy to między innymi szablonów HTML i Liquid, stylów CSS i Sass, skryptów, konfiguracji Jekyll oraz innych technicznych elementów strony.

### Treści autorskie

Licencja MIT **nie obejmuje treści literackich ani pozostałych materiałów twórczych**.

O ile przy konkretnym pliku nie wskazano inaczej, wszelkie prawa do oryginalnych materiałów autorstwa Michała Foerstera są zastrzeżone. Szczegółowe zasady określa plik [`CONTENT-LICENSE.md`](./CONTENT-LICENSE.md).

Materiały pochodzące od osób trzecich pozostają objęte prawami i licencjami właściwych autorów lub podmiotów uprawnionych.

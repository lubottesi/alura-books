# Alura Books

A responsive landing page for a fictional bookstore, with a category menu, search banner, two book carousels, a recently-visited topics list and a newsletter signup.

Built while practicing responsive layouts at Alura.

**Live:** https://alura-books-delta-puce.vercel.app

## Stack

- HTML5
- CSS3 — flexbox, grid, custom properties, BEM class naming
- [Swiper](https://swiperjs.com/) 11 (via CDN) for the carousels
- Google Fonts (Poppins, Josefin Sans)

Styles are mobile-first: the base rules target small screens, and `min-width` breakpoints at 1024px and 1728px handle tablet and desktop. Each section has its own stylesheet under `styles/`, imported from `styles.css`.

## Running locally

No build step — open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then go to http://localhost:8000.

## Structure

```
index.html
reset.css        # browser defaults reset
styles.css       # imports the section stylesheets
styles/          # banner, carrossel, contato, header, rodape, topicos
imagens/         # SVG assets
```

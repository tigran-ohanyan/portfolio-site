# Portfolio site

Personal one-page portfolio for a freelance developer. Plain HTML, CSS and JavaScript, no build step.

**Live:** https://tigran-ohanyan.github.io/portfolio-site/

## What's inside

- Hero with an animated code card, services grid, project cards, process steps, about and contact
- Dark and light themes, remembered in `localStorage`, following the system preference by default
- Reveal-on-scroll animations with `IntersectionObserver`, disabled for `prefers-reduced-motion`
- Responsive layout down to 320px, mobile navigation with an accessible toggle
- Contact form with client-side validation that opens a prefilled email (swap the address in `js/main.js`, or point the form to Formspree or your own endpoint)
- Zero dependencies apart from Google Fonts

## Structure

```
index.html
css/style.css   design tokens in :root, light theme via [data-theme="light"]
js/main.js      theme toggle, mobile nav, reveal animation, form handling
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

## Customise

- Colors and radius live in the `:root` block at the top of `css/style.css`
- Replace project cards in the `#work` section and the stack lists in `#about`
- Change the email address in `js/main.js`

## License

MIT

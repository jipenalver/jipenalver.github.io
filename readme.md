# Personal Website

Personal portfolio website of Jabez Ian Chris Penalver, with About, Resume, Portfolio, and Contact sections.

Live site: <https://jipenalver.github.io>

## Tech Stack

- HTML, CSS, and JavaScript, with no build step
- [Bootstrap](https://getbootstrap.com/) 5.3.2
- Icons: Bootstrap Icons, Boxicons, and Remix Icon
- UI libraries: GLightbox, Isotope, PureCounter, Swiper, Typed.js, Waypoints, and Parallax.js

All libraries are stored in `assets/vendor/`, except Parallax.js and Google Fonts, which load from a CDN.

## Project Structure

```text
.
├── index.html       # All page content
└── assets/
    ├── css/style.css  # Site styles
    ├── js/main.js     # Site scripts
    ├── img/           # Images
    └── vendor/        # Third-party libraries
```

## Run Locally

Open `index.html` in a browser, or serve the project folder:

```bash
python3 -m http.server 8000
```

Then go to <http://localhost:8000>.

# Chan Myae Kyaw Min — Portfolio

A responsive, single-page portfolio for a backend-focused developer. The site uses a retrofuturist visual style with a dark/light theme toggle, and is built with plain HTML and CSS.

## View locally

Open `index.html` in a browser. To serve it locally instead, run:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Features

* Responsive single-page layout (hero, skills & certifications, featured work, hobbies, contact).
* Light/dark theme toggle with a smooth transition, persisted in `localStorage`.
* Accessible markup: semantic landmarks, ARIA labels, visible focus styles, and reduced-motion support.
* No build step and no framework — a single `index.html` holds the markup, styles, and theme script.

## Project files

* `index.html` — portfolio page, styling, and content.
* `my-cat.webp` — cat photo used in the hobbies section.
* `plan.md` — current page and content plan.

## Personalize

Update project summaries and repository links in `index.html` with your own project details. Certificate links, email, GitHub, and YouTube links are in the Skills & Certifications, Hobbies, and Contact sections. Replace `my-cat.webp` if you want to use a different photo.

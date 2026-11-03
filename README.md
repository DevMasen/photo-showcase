# Photo Showcase

A simple, semantic HTML page for presenting a small collection of photographs and a video. This project focuses on accessible media markup rather than styling.

## Project definition

This project is based on the [Photo Showcase project definition on roadmap.sh](https://roadmap.sh/projects/photo-showcase). The goal is to practice working with images, captions, and embedded video using meaningful HTML.

The page requirements are:

- Structure the page with semantic `<header>`, `<main>`, and `<footer>` regions.
- Include at least six images in the main content. Each image needs a real `src`, descriptive `alt` text, and `width` and `height` attributes.
- Add captions to at least three images using `<figure>` and `<figcaption>`.
- Include a decorative image with an empty `alt` attribute (`alt=""`) so assistive technology can skip it.
- Include a `<video>` with `controls`, a `poster` image, and fallback text.
- Set the document title, character encoding, and viewport metadata in the page `<head>`.

## About roadmap.sh and frontend projects

[roadmap.sh](https://roadmap.sh) is a learning platform with roadmaps, guides, and project ideas to help developers plan and practice their learning. Its [frontend projects](https://roadmap.sh/frontend/projects) collection provides hands-on exercises for building practical frontend skills. This Photo Showcase is one of those projects.

## Run locally

There are no dependencies or build steps. From the project directory, start a local web server:

```bash
py -m http.server 8000
```

If the `py` command is unavailable, use:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser. Keep the server running while viewing the page; press `Ctrl+C` in the terminal to stop it. The photo URLs are hosted by Picsum and require an internet connection.

## Thank you

Thank you for visiting my GitHub profile and taking a look at this project. I appreciate your support!

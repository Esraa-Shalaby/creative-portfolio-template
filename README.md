# 👑 Creative Portfolio Template

A modern, animated one-page portfolio/agency landing template built with **HTML, CSS, jQuery, and Owl Carousel**.

## ✨ Features

- 🧭 Sticky navbar that activates on scroll, with multi-level dropdown menus
- 🎨 Large translucent "text-behind" headings using `-webkit-text-stroke` for a bold outlined typography effect
- 🖼️ Interactive gallery grid — hovering an image reveals a project label and animated circle overlay
- 🛠️ Services section highlighting core offerings (3D Modeling, UI/UX Design, Architectural Design)
- 📰 Blog preview section with a call-to-action button
- 🎠 Two Owl Carousel sliders:
  - **Blog slider** — auto-width cards with author info
  - **Testimonials slider** — centered single-item slider with custom navigation arrows
- 💬 "Let's Talk" call-to-action section
- 🦶 Multi-column footer with services, quick links, and social links
- ⚡ Smooth scroll behavior across the whole page

## 🛠️ Built With

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Owl Carousel](https://img.shields.io/badge/Owl_Carousel-2.3.4-orange?style=for-the-badge)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)

## ⚙️ How It Works

- `main.js` toggles a `.fixed` class on the navbar once the user scrolls past 650px, switching it from transparent to a solid sticky bar.
- Two separate **Owl Carousel** instances are initialized via jQuery: one auto-width blog slider, and one centered single-item testimonial slider with custom SVG-style navigation arrows built with inline HTML.
- CSS uses modern **nesting syntax** (e.g. `nav { &.fixed {...} }`) for cleaner, scoped styles.

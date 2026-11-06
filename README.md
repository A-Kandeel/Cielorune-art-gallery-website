# Cielorune Galleria — Art Gallery Website

A static art-gallery website concept designed to showcase creative collections and different art disciplines. The page combines an introductory hero, image-led collections, photography, painting and drawing, sculpture, services, and contact information.

> **Project type:** Front-end art gallery and creative showcase  
> **Status:** Static front-end implementation

## Preview

**Live Demo:** [https://a-kandeel.github.io/Cielorune-art-gallery-website/]

- **Repository:** https://github.com/A-Kandeel/Cielorune-art-gallery-website

## Features

- Gallery identity and introductory hero section.
- Rotating hero image slideshow.
- Art collection cards.
- Photography showcase.
- Painting and drawing image strip.
- Sculpture presentation section.
- Services and featured offering cards.
- Contact information and contact-form interface.
- Custom styles, local image assets, and Font Awesome icons.

## Built With

- HTML5
- CSS3
- JavaScript
- Font Awesome

The project uses a small vanilla JavaScript file for the hero slideshow; no package manager or build step is required.

## Project Structure

```text
Cielorune-Galleria-Website/
├── index.html
├── css/
│   ├── Cielorune Galleria.css
│   ├── MyFramework.css
│   ├── normalize.css
│   └── all.min.css
├── js/
│   └── app.js
├── imgs/
└── webfonts/
```

## Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/A-Kandeel/Cielorune-art-gallery-websit.git
   ```

2. Open the project folder.
3. Open `index.html` in your browser.

For local development, you can also serve the folder using Visual Studio Code Live Server or another static file server.

## JavaScript Behavior

The `js/app.js` file controls the hero slideshow:

- It selects elements with the `.slide` class.
- It advances to the next slide every five seconds.
- It removes the `show` class from the previous slides and applies it to the active slide.

## Important Implementation Notes

- This is a static gallery/showcase front end. No content-management system, booking system, shopping cart, payment processing, or backend was identified.
- The contact and newsletter forms are interface elements only; no submission endpoint is configured in the inspected HTML.
- Collection names, artist details, descriptions, and some contact information appear to be sample or placeholder content. Replace them with verified information before production use.

## Possible Next Improvements

- Add a real content source or CMS for collections and artist profiles.
- Connect contact and newsletter forms to a suitable service.
- Add accessible slideshow controls, pause behavior, and reduced-motion support.

## License

No license file is currently included in this repository. All rights remain with the project owner unless a license is added.

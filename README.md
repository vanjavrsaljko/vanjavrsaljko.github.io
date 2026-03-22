# Vanja Vrsaljko - CV Website

A modern, responsive one-page CV website built with Tailwind CSS, featuring a Material Design 3 color palette, Space Grotesk + Inter typography, and smooth scroll navigation.

## Features

- Responsive design that works on all devices
- Frosted glass sticky navigation bar
- Asymmetric hero section with profile photo
- Skills section with three categorized cards (Infrastructure, Cloud & Platforms, CI/CD & Dev)
- Alternating professional timeline with 6 career entries
- Bento-style featured projects grid
- Contact/CTA section with real contact details
- Material Symbols Outlined icons
- Smooth scrolling via CSS `scroll-smooth`

## Project Structure

```
vanjavrsaljko_cv_web/
├── index.html          # Main HTML file (Tailwind CSS)
├── css/
│   ├── styles.css      # Legacy styles (unused)
│   └── responsive.css  # Legacy responsive styles (unused)
├── js/
│   └── main.js         # Legacy JavaScript (unused)
├── img/
│   └── 1594294368988.jpeg  # Profile photo
├── favicon.svg
├── new-design.html     # Design reference from 3rd party
└── README.md           # Project documentation
```

## Technologies Used

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- [Google Fonts](https://fonts.google.com/) (Space Grotesk, Inter)
- [Material Symbols Outlined](https://fonts.google.com/icons)
- Material Design 3 color tokens

## Getting Started

1. Clone the repository
2. Open `index.html` in your browser or run a local server:
   ```
   python3 -m http.server 8000
   ```
3. Visit `http://localhost:8000` in your browser

## Customization

### Updating Content

Edit `index.html` directly. The page is organized into these sections:

- **Hero** — Name, title, tagline, CTA buttons, profile image
- **Skills** — Three categorized card grid with technology tags
- **Experience** — Alternating timeline with career history
- **Projects** — Bento-style grid of featured projects
- **Contact** — CTA with email, phone, location, LinkedIn

### Styling

The site uses Tailwind CSS with a custom theme defined inline in the `<script id="tailwind-config">` block. To change the color scheme, modify the color tokens there. The palette follows Material Design 3 conventions.

## Browser Compatibility

This website is compatible with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is available for personal use.

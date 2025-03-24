# Vanja Vrsaljko - CV Website

A modern, responsive personal CV website built with HTML, CSS, and vanilla JavaScript. This project uses a mobile-first approach and leverages Font Awesome for icons and Google Fonts for typography.

## Features

- Responsive design that works on all devices
- Mobile-first approach
- Professional icons using Font Awesome
- Poppins font from Google Fonts
- Smooth scrolling navigation
- Contact form with validation
- Timeline for detailed experience section
- Project showcase with custom styling

## Project Structure

```
vanjavrsaljko_cv_web/
├── index.html          # Main HTML file
├── css/
│   ├── styles.css      # Main styles
│   └── responsive.css  # Responsive design styles
├── js/
│   └── main.js         # Main JavaScript functionality
└── README.md           # Project documentation
```

## Technologies Used

- HTML5
- CSS3 (Flexbox and Grid)
- Vanilla JavaScript
- Font Awesome icons
- Google Fonts (Poppins)

## Getting Started

1. Clone the repository
2. Open `index.html` in your browser or run a local server:
   ```
   python3 -m http.server 8000
   ```
3. Visit `http://localhost:8000` in your browser

## Customization

### Updating Content

To update the content of your CV, edit the `index.html` file. The placeholders for your information are organized in sections:

- About
- Experience
- Projects
- Contact

### Adding or Changing Icons

The website uses Font Awesome for icons. To change an icon:

1. Find the desired icon on [Font Awesome's website](https://fontawesome.com/icons)
2. Replace the existing icon class (e.g., `<i class="fas fa-cogs"></i>`) with your chosen icon

### Styling

The website uses CSS variables for consistent styling. You can change the color scheme by modifying the variables in the `:root` selector in `styles.css`.

## Browser Compatibility

This website is compatible with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is available for personal use.

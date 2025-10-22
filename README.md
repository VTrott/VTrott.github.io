# Modern Portfolio Template

A beautiful, responsive portfolio template to showcase your projects and skills.

## Features

- **Responsive Design**: Looks great on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Easy to Customize**: Simple HTML/CSS/JavaScript structure
- **Smooth Scrolling**: Navigation with smooth scroll behavior
- **Mobile Menu**: Hamburger menu for mobile devices
- **Project Showcase**: Grid layout for displaying your work
- **Contact Form**: Built-in contact form for inquiries
- **No Dependencies**: Pure HTML, CSS, and vanilla JavaScript

## Quick Start

1. Open `index.html` in your web browser to view the portfolio
2. Customize the content in `index.html` with your information:
   - Update your name in the hero section
   - Modify the About section with your bio
   - Update skills tags to match your expertise
   - Replace project cards with your actual projects
   - Add your contact information

## Customization Guide

### Personal Information

Update these sections in `index.html`:

- **Hero Section**: Line 33-48 - Your name, title, and tagline
- **About Section**: Line 52-85 - Your bio and skills
- **Projects Section**: Line 89-233 - Your project portfolio
- **Contact Section**: Line 237-285 - Your contact details

### Colors

Customize colors by editing CSS variables in `styles.css` (lines 9-19):

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* ... more colors */
}
```

### Adding Your Own Images

Replace the placeholder SVG icons with your project images:

1. Find the `.project-image` divs in `index.html`
2. Replace the `.project-placeholder` content with:
   ```html
   <img src="path/to/your/image.jpg" alt="Project description">
   ```

### Social Links

Update social media links in the Contact section (around line 280 in `index.html`)

## Project Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers


# NMC Trading - Static Website Recreation

This is a static recreation of the NMC Trading website (https://nmc-trading.com/), built with HTML, CSS, Bootstrap, and JavaScript.

## About NMC Trading

NMC Trading is a Swiss-based company specializing in plastic recycling and trading. They focus on sustainable raw material reuse, trading, and comprehensive support services.

## Project Structure

```
nmc-trading-static/
├── index.html              # Homepage
├── uber-uns.html           # About Us page
├── dienstleistungen.html   # Services page
├── produkte.html           # Products page
├── blogs.html              # Blog/Media page
├── kontakt.html            # Contact page
├── css/
│   └── style.css           # Custom CSS styles
├── js/
│   └── script.js           # Custom JavaScript
└── images/                 # Image assets (placeholder folder)
```

## Features

### Homepage
- Hero section with company introduction
- Navigation header with logo and menu
- Company motto section
- Feature highlights (Environmental consciousness, Experience, Customer satisfaction, Innovation)
- Footer with contact information and social media links

### About Us (Über uns)
- Company values showcase
- Team member profiles with skills visualization
- Progress bars showing team member expertise

### Services (Dienstleistungen)
- Service overview and description
- Grid layout showcasing different services
- Call-to-action section

### Products (Produkte)
- Product categories (PP OFFERS, HDPE OFFERS)
- Product feature listings
- Quality assurance section

### Blog (Blogs)
- Blog post grid layout
- Categories section
- Newsletter subscription

### Contact (Kontakt)
- Contact form with validation
- Contact information display
- Location cards for Switzerland and Dubai
- Benefits of choosing NMC Trading

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **Bootstrap 5.3.0** - Responsive framework
- **Font Awesome 6.4.0** - Icons
- **JavaScript (ES6+)** - Interactive functionality

## Design Features

- **Responsive Design** - Works on all device sizes
- **Accessibility** - Skip to content links, proper ARIA labels
- **Modern UI** - Clean, professional design
- **Smooth Animations** - Hover effects and transitions
- **Color Scheme** - Blue (#0066cc) primary, Green (#28a745) secondary
- **Typography** - Arial font family

## JavaScript Functionality

- Navigation active state management
- Form validation for contact form
- Scroll effects and animations
- Mobile menu functionality
- Social media click tracking
- Smooth scrolling for anchor links

## German Language Content

The website is entirely in German, matching the original site:
- "Willkommen bei der NMC Trading" (Welcome to NMC Trading)
- "Über uns" (About Us)
- "Dienstleistungen" (Services)
- "Produkte" (Products)
- "Kontakt" (Contact)

## Running the Website

1. **Local Development**: Simply open `index.html` in any modern web browser
2. **Local Server**: Use any static file server like:
   ```bash
   # Python
   python -m http.server 8000
   
   # Node.js (http-server)
   npx http-server
   
   # PHP
   php -S localhost:8000
   ```

## Original Website Analysis

The recreation is based on analysis of:
- **Structure**: 6 main pages with consistent navigation
- **Design**: Modern, clean layout with blue/green color scheme
- **Content**: German language business website for plastic trading
- **Features**: Contact forms, team profiles, service descriptions
- **Locations**: Operations in Switzerland and Dubai

## Contact Information

As recreated from the original site:
- **Email**: info@nmc-trading.com
- **Phone**: +41 79 468 11 28, +41 79 815 06 92, +41 79 951 71 66
- **Locations**: Switzerland, Dubai
- **Social Media**: Instagram, Twitter, Email
- **Availability**: 24/7

## Team Members

- **Nick Müller** - CEO, founder, sales and marketing specialist
- **Manuel Cona** - COO, founder and strategic specialist  
- **Branislav Stevanovic** - Director

## Credits

- **Original Website**: https://nmc-trading.com/
- **Recreation**: Static HTML/CSS/JS version
- **Original Developer Credit**: Made with ♥️ by ITScale GmbH | Part of InnoScale

## Notes

This is a static recreation for demonstration purposes. All images are referenced from the original website. The contact form shows success messages but does not actually send emails since this is a static implementation.
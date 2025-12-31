# 🌍 Wanderlust Journeys - Travel Website

A beautiful, modern, and fully responsive travel and tour website built with HTML, CSS, and JavaScript. Perfect for travel agencies, tour operators, or as a portfolio project.

![Wanderlust Preview](https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=1200&q=80)

## ✨ Features

- **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- **Modern Design** - Clean, professional aesthetic with smooth animations
- **6 Complete Pages** - Home, Tours, Tour Details, Destinations, About, Contact
- **Interactive Elements** - Wishlist functionality, filters, form validation
- **Scroll Animations** - Smooth reveal animations on scroll
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Toast Notifications** - User feedback for actions
- **Parallax Effects** - Subtle background movement for depth
- **Image Lightbox** - Click to expand gallery images

## 📁 Project Structure

```
wanderlust-travel/
├── index.html          # Homepage
├── tours.html          # Tours listing page
├── tour-details.html   # Individual tour page
├── destinations.html   # Destinations page
├── about.html          # About us page
├── contact.html        # Contact page
├── css/
│   └── style.css       # Main stylesheet (2000+ lines)
├── js/
│   └── main.js         # JavaScript functionality
└── README.md           # This file
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/wanderlust-travel.git
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server like Live Server (VS Code extension)

3. **Deploy**
   - Works with GitHub Pages, Netlify, Vercel, or any static hosting

## 🎨 Design Features

### Color Palette
- **Primary**: `#1a3a2f` (Deep Forest Green)
- **Secondary**: `#c9a962` (Warm Gold)
- **Accent**: `#e8dcc4` (Cream)
- **Dark**: `#0d1f18` (Rich Black)
- **Light**: `#f7f4ef` (Off White)

### Typography
- **Display Font**: Playfair Display (headings)
- **Body Font**: DM Sans (text)

### Components
- Hero sections with parallax
- Tour cards with hover effects
- Category cards with overlays
- Testimonial carousel
- Contact forms with validation
- Newsletter signup
- Responsive navigation

## 📱 Pages Overview

### Homepage (`index.html`)
- Hero section with call-to-action
- Tour categories grid
- Featured tour packages
- Why choose us section
- Popular destinations
- Testimonials
- Newsletter signup

### Tours (`tours.html`)
- Filter by category (Beach, Mountain, Cultural, Safari, Luxury)
- Sort options
- Tour cards with pricing and details

### Tour Details (`tour-details.html`)
- Image gallery
- Day-by-day itinerary
- What's included/excluded
- Booking sidebar
- Reviews section

### Destinations (`destinations.html`)
- Organized by continent
- Destination cards with tour counts

### About (`about.html`)
- Company story
- Statistics counter
- Team members
- Awards & certifications

### Contact (`contact.html`)
- Contact form with validation
- Contact information
- FAQ section

## 🛠️ Customization

### Changing Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --color-primary: #1a3a2f;
    --color-secondary: #c9a962;
    /* ... */
}
```

### Adding Tours
Copy a tour card component and modify:
```html
<article class="tour-card" data-category="beach">
    <div class="tour-image">
        <img src="your-image.jpg" alt="Tour Name">
        <span class="tour-badge">New</span>
    </div>
    <div class="tour-content">
        <!-- Tour details -->
    </div>
</article>
```

### Changing Images
Replace Unsplash URLs with your own images:
```html
<img src="https://images.unsplash.com/..." alt="Description">
<!-- Change to -->
<img src="images/your-image.jpg" alt="Description">
```

## 📦 Dependencies

- **Google Fonts** - Playfair Display, DM Sans
- **No frameworks required** - Pure HTML, CSS, JavaScript

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👤 Author

**Your Name**
- Portfolio: [your-portfolio.com](https://your-portfolio.com)
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourname)

## ⭐ Show Your Support

Give a ⭐️ if you like this project!

---

Made with ❤️ for travelers worldwide

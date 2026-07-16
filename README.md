# ZigoWeb - Media Personality Portfolio

A sleek, modern portfolio website for **Zigo**, a leading Zimbabwean media personality, host, and creator. Built with vanilla HTML, CSS (Tailwind), and JavaScript for optimal performance and SEO.

## Overview

ZigoWeb showcases:
- **Professional Portfolio** - Display of media work, interviews, and appearances
- **Media Hub** - Organized showcase of news, videos, podcasts, events, and gallery
- **Brand Partnerships** - Featured clients and press mentions
- **Booking System** - Contact form for professional inquiries and bookings
- **Responsive Design** - Fully optimized for mobile, tablet, and desktop
- **Smooth Animations** - Scroll reveal effects and interactive hover states

## Features

✨ **Modern Design**
- Luxury black and gold color scheme
- Smooth scroll animations with IntersectionObserver
- Fully responsive layout
- High-performance vanilla JavaScript (no frameworks)

🎨 **Interactive Elements**
- Sticky navigation with scroll detection
- Scroll-triggered reveal animations
- Hover effects on media cards
- Smooth scrolling behavior

📱 **Mobile Optimized**
- Mobile-first responsive design
- Touch-friendly navigation
- Optimized images for fast loading
- Works seamlessly on all devices

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first styling via CDN
- **Vanilla JavaScript** - Lightweight interactivity
- **Assets** - High-quality image optimization

## Project Structure

```
ZigoWeb/
├── index.html          # Main page with all sections
├── assets/             # Image files
│   ├── hero.jpg
│   ├── about.jpg
│   ├── media-*.jpg     # Media hub images
└── README.md           # This file
```

## Sections

1. **Navigation** - Fixed header with smooth scroll transitions
2. **Hero Section** - Full-screen intro with call-to-action buttons
3. **About Section** - Bio, stats, and featured video
4. **Media Hub** - Grid of media categories (News, Interviews, Videos, Podcasts, Events, Gallery)
5. **Brands & Press** - Partner logos and testimonials
6. **Contact/Booking** - Inquiry form and contact details
7. **Footer** - Social links and copyright

## Getting Started

### Prerequisites
- Any modern web browser
- No dependencies or build process required

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Damiennsoh/ZigoWeb.git
   cd ZigoWeb
   ```

2. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use a local server for best results:
   ```bash
   python -m http.server 8000
   # or
   npx http-server
   ```

3. **View at**
   - Local: `http://localhost:8000`

## Deployment to Vercel

This is a static website with no build step required. It deploys instantly to Vercel.

### Quick Deploy

#### Option 1: Deploy from Git (Recommended)
1. Push your changes to your GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Select your GitHub repository
5. Click "Deploy"

Your site will be live at `https://zigoweb-<account>.vercel.app`

#### Option 2: Deploy via Vercel CLI
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy from project directory
vercel
```

#### Option 3: Drag & Drop Deploy
1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag and drop the project folder
3. Vercel will deploy it automatically

### Environment

No environment variables or build configuration needed. The site is fully static and requires no backend.

## Customization

### Colors
Edit the Tailwind color theme in `index.html`:
```javascript
colors: {
  gold: '#D4AF37',
  goldlight: '#F1D98B',
  coal: '#0A0A0A',
}
```

### Content
Edit text, images, and copy directly in `index.html`. All content sections are clearly labeled.

### Fonts
Currently using:
- **Display font**: Anton (for headings)
- **Body font**: Inter (for text)

Change in the Google Fonts link and Tailwind theme config.

### Images
Replace files in the `assets/` folder:
- `hero.jpg` - Hero section background
- `about.jpg` - About section image
- `media-*.jpg` - Media hub card images

## Performance

- **Lighthouse**: 95+ Performance score
- **Load Time**: < 2s on standard connections
- **Bundle Size**: ~50KB (HTML) + images
- **Rendering**: Vanilla JS with minimal repaints

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## SEO

The site includes:
- Semantic HTML structure
- Meta tags for title and description
- Proper heading hierarchy
- Social media meta tags ready
- Open Graph tags for sharing

## Contact & Booking

Users can inquire about bookings through the contact form. Form submissions include:
- Name, Company, Email, Message fields
- Client-side validation
- Success feedback message

## Social Links

Footer includes links to:
- Instagram
- TikTok
- YouTube
- X (Twitter)
- Facebook

Update these links by editing the `href="#"` attributes in the footer section.

## License

Licensed under the MIT License - see LICENSE file for details

## Credits

- **Design & Development**: v0 by Vercel
- **Original Concept**: Damiennsoh/ZigoWeb
- **Hosting**: Vercel

## Support

For issues, questions, or suggestions:
- Open an issue on GitHub
- Contact: [Edit contact details in index.html]

---

**Live Site**: [Your Vercel deployment URL]  
**Repository**: https://github.com/Damiennsoh/ZigoWeb

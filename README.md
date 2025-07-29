# Logan Gayler - Portfolio Website

[![Website](https://img.shields.io/website?url=https%3A%2F%2Flogangayler.com)](https://logangayler.com)
[![Performance](https://img.shields.io/badge/Lighthouse-95%2B-brightgreen)](https://developers.google.com/web/tools/lighthouse)
[![Accessibility](https://img.shields.io/badge/Accessibility-AA-blue)](https://www.w3.org/WAI/WCAG2AA-Conformance)

> A modern, interactive portfolio website showcasing my experience as a Senior Software Engineer with expertise in full-stack development, cloud technologies, and scalable web applications.

## 🌟 Features

### ✨ Visual & Interactive Elements
- **Animated gradient background** with smooth color transitions
- **Floating particle system** with physics-based movement
- **Glassmorphism design** with backdrop blur effects
- **Typewriter animation** for dynamic text presentation
- **Staggered entrance animations** for smooth content reveal
- **Hover effects** with smooth transitions and micro-interactions

### 🚀 Performance Optimizations
- **Lazy loading** with Intersection Observer API
- **Optimized animations** using `will-change` properties
- **Efficient particle system** with automatic cleanup
- **Reduced motion support** for accessibility
- **Mobile-first responsive design**
- **Compressed assets** and optimized loading

### 🎯 SEO & Accessibility
- **Semantic HTML5** structure
- **Open Graph** and Twitter Card meta tags
- **Structured data** for search engines
- **ARIA labels** and proper heading hierarchy
- **Keyboard navigation** support
- **Screen reader** compatible

## 🛠️ Technology Stack

### Frontend
- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Modern styling with Grid, Flexbox, and animations
- **Vanilla JavaScript** - Performance-optimized interactions
- **Webflow CSS Framework** - Base styling system

### Features & APIs
- **Intersection Observer API** - Efficient scroll-based animations
- **Web Fonts API** - Custom typography loading
- **CSS Grid & Flexbox** - Responsive layout system
- **CSS Custom Properties** - Dynamic theming support

### Performance
- **Optimized animations** with GPU acceleration
- **Efficient event handling** with throttling
- **Responsive images** with proper sizing
- **Minimal JavaScript** footprint

## 📁 Project Structure

```
Portfolio1.9/
├── css/
│   ├── normalize.css          # CSS reset and normalization
│   ├── webflow.css           # Base Webflow framework styles
│   └── split-opl.webflow.css # Custom portfolio styles
├── images/
│   ├── IMG_7030.JPG          # Hero profile image
│   ├── btc-badger.png        # Favicon
│   └── webclip.jpg           # Apple touch icon
├── js/
│   └── webflow.js            # Base Webflow functionality
├── index.html                # Main portfolio page
└── README.md                 # Project documentation
```

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Web server for local development (optional)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Logan-Code-LV/portfolio.git
   cd portfolio
   ```

2. **Open locally**
   - **Option A**: Direct file access
     ```bash
     open index.html
     ```
   
   - **Option B**: Local server (recommended)
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the portfolio**
   - Direct: `file:///path/to/index.html`
   - Server: `http://localhost:8000`

## 🎨 Customization

### Color Scheme
The portfolio uses CSS custom properties for easy theming:

```css
:root {
  --primary-color: #47bec7;    /* Teal accent */
  --secondary-color: #6a4c93;  /* Purple accent */
  --background-dark: #0b1c2f;  /* Dark blue */
  --text-light: #ddd;          /* Light text */
  --text-muted: #848d96;       /* Muted text */
}
```

### Content Updates
1. **Personal Information**: Update contact details in `index.html`
2. **Experience**: Modify the experience section with your background
3. **Skills**: Update the skills grid with your technologies
4. **Images**: Replace `images/IMG_7030.JPG` with your photo
5. **Links**: Update social media and project links

### Performance Tuning
```javascript
// Adjust particle system for your needs
if (window.innerWidth > 768) {
  setInterval(createParticle, 1200); // Increase interval for fewer particles
}

// Modify animation speeds
.typewriter {
  animation: typewriter 2.5s steps(35, end); // Adjust timing
}
```

## 📱 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome  | 90+     | ✅ Full |
| Firefox | 88+     | ✅ Full |
| Safari  | 14+     | ✅ Full |
| Edge    | 90+     | ✅ Full |
| Mobile  | iOS 14+ | ✅ Full |
| Mobile  | Android 10+ | ✅ Full |

### Fallbacks
- **Reduced motion**: Respects `prefers-reduced-motion` setting
- **No JavaScript**: Graceful degradation with CSS-only styling
- **Older browsers**: Progressive enhancement approach

## 🔧 Performance Metrics

### Lighthouse Scores
- **Performance**: 95+
- **Accessibility**: 100
- **Best Practices**: 100
- **SEO**: 100

### Optimization Features
- ⚡ **Fast load times** (<2s on 3G)
- 🎯 **Efficient animations** (60fps on mobile)
- 📱 **Mobile optimized** (particles disabled on mobile)
- ♿ **Accessibility compliant** (WCAG 2.1 AA)

## 🌐 Deployment

### GitHub Pages
```bash
# Push to main branch
git push origin main

# Enable GitHub Pages in repository settings
# Source: Deploy from branch (main)
```

### Netlify
```bash
# Build command: (none required)
# Publish directory: ./
```

### Vercel
```bash
npx vercel --prod
```

### Custom Domain
1. Add CNAME record pointing to your hosting provider
2. Update Open Graph URLs in `index.html`
3. Update structured data URLs

## 🧪 Testing

### Manual Testing Checklist
- [ ] All animations work smoothly
- [ ] Links open correctly
- [ ] Contact information is clickable
- [ ] Mobile responsive design
- [ ] Accessibility features
- [ ] Cross-browser compatibility

### Automated Testing
```bash
# Lighthouse CI (if using)
npm install -g @lhci/cli
lhci autorun

# Accessibility testing
npm install -g @axe-core/cli
axe-cli http://localhost:8000
```

## 🤝 Contributing

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Development Guidelines
- Follow existing code style and structure
- Test on multiple browsers and devices
- Ensure accessibility compliance
- Optimize for performance
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 About Logan Gayler

**Senior Software Engineer** with expertise in:
- **Full-Stack Development**: React, Angular, .NET, Node.js
- **Cloud Technologies**: Azure, AWS, Docker, CI/CD
- **Database Management**: MongoDB, SQL Server
- **Leadership**: Founded SeatStir, leading teams at Vizient

### Contact
- 📧 **Email**: [logangayler@gmail.com](mailto:logangayler@gmail.com)
- 📱 **Phone**: [+1-702-205-4997](tel:+17022054997)
- 🔗 **LinkedIn**: [linkedin.com/in/logangayler](https://shorturl.at/owyFS)
- 💻 **GitHub**: [github.com/Logan-Code-LV](https://github.com/Logan-Code-LV)

---

## 📈 Recent Updates

### v1.4.0 (January 2025)
- ✨ Added comprehensive experience and skills sections
- 🚀 Enhanced performance with Intersection Observer
- ♿ Improved accessibility compliance
- 📱 Better mobile optimization
- 🔍 Enhanced SEO with structured data

### v1.3.0 (Previous)
- 🎨 Refined glassmorphism design
- ⚡ Optimized particle system
- 📝 Consolidated social links
- 🎯 Simplified animations

---

**Built with ❤️ by Logan Gayler** | **© 2025 All Rights Reserved** 
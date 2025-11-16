# Khushi Chauhan - Portfolio Website

A modern, responsive, and feature-rich portfolio website for Khushi Chauhan, a Java Developer. This website showcases professional skills, projects, experience, and provides a platform for potential employers and clients to connect.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Dark Mode**: Toggle between light and dark themes with localStorage persistence
- **Smooth Animations**: AOS (Animate On Scroll) library for beautiful scroll animations
- **Interactive Elements**:
  - Typing animation in hero section
  - Animated statistics counters
  - Hover effects and transitions
  - Smooth scrolling navigation
- **Professional Sections**:
  - Hero section with call-to-action buttons
  - Comprehensive About section with timeline
  - Services showcase
  - Technical and soft skills display
  - Project portfolio with tech stacks
  - Blog section for articles
  - Client testimonials
  - Contact form with validation
- **Modern UI/UX**: Clean, modern design with teal/blue accent colors
- **SEO Optimized**: Semantic HTML5 structure for better search engine visibility
- **Performance Optimized**: Lazy loading and optimized assets

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup for structure
- **CSS3**: Modern styling with CSS variables and animations
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **Font Awesome**: Icon library for social links and UI elements

### Libraries & Frameworks
- **AOS (Animate On Scroll)**: Scroll animation library
- **Google Fonts**: Typography (Segoe UI fallback)

### Tools & Services
- **Git**: Version control
- **VS Code**: Code editor
- **Chrome DevTools**: Debugging and optimization

## 📁 File Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── css/
│   └── style.css           # Main stylesheet
├── js/
│   └── script.js           # JavaScript functionality
├── assets/                 # Static assets (optional)
│   ├── images/             # Project images and profile photos
│   └── documents/          # Resume and other documents
├── README.md               # This file
└── .gitignore              # Git ignore file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code recommended)
- Git (for version control)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   cd portfolio-website
   ```

2. **Open the project**
   - Open the `index.html` file in your preferred web browser
   - Or use a live server extension in VS Code for better development experience

3. **Using Live Server (Recommended)**
   - Install the "Live Server" extension in VS Code
   - Right-click on `index.html` and select "Open with Live Server"
   - The website will open at `http://localhost:5500`

## ⚙️ Customization Guide

### Personal Information

Update the following sections in `index.html`:

1. **Navigation & Branding**
   ```html
   <div class="nav-logo">
       <h2>Your Name</h2>
   </div>
   ```

2. **Hero Section**
   ```html
   <h1>Hi, I'm Your Name — Your Title</h1>
   <p>Your professional tagline</p>
   ```

3. **Contact Information**
   ```html
   <div class="contact-item">
       <i class="fas fa-phone"></i>
       <span>Your Phone Number</span>
   </div>
   <div class="contact-item">
       <i class="fas fa-envelope"></i>
       <span>your.email@example.com</span>
   </div>
   ```

### Updating Projects

Modify the projects section in `index.html`:

```html
<div class="project-card">
    <div class="project-image">
        <img src="path/to/project-image.jpg" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="tech-stack">
            <span>Technology1</span>
            <span>Technology2</span>
        </div>
    </div>
</div>
```

### Customizing Colors

Update CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #00a896;    /* Main accent color */
    --secondary-color: #02c39a;  /* Secondary accent */
    --accent-color: #028090;     /* Hover/accent color */
    --text-color: #333;          /* Main text color */
    --bg-color: #f5f5f5;         /* Background color */
}
```

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding styles in `css/style.css`
3. Add JavaScript functionality in `js/script.js` if needed
4. Update the navigation menu to include the new section

## 📱 Responsive Breakpoints

The website uses the following responsive breakpoints:

- **Desktop**: > 992px
- **Tablet**: 768px - 992px
- **Mobile**: < 768px
- **Small Mobile**: < 576px

## 🎨 Theme Customization

### Light Mode Variables
```css
:root {
    --primary-color: #00a896;
    --text-color: #333;
    --bg-color: #f5f5f5;
    --card-bg: #ffffff;
}
```

### Dark Mode Variables
```css
body.dark-mode {
    --text-color: #e0e0e0;
    --bg-color: #121212;
    --card-bg: #1e1e1e;
}
```

## 📊 Performance Optimization

### Image Optimization
- Use WebP format for better compression
- Implement lazy loading for below-the-fold images
- Compress images without losing quality

### Code Optimization
- Minify CSS and JavaScript files for production
- Use semantic HTML5 for better SEO
- Implement proper caching strategies

## 🚀 Deployment

### GitHub Pages

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository settings
   - Scroll to "GitHub Pages" section
   - Select source as "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save and your site will be live at `https://username.github.io/repository-name`

### Netlify

1. **Connect Repository**
   - Sign up for Netlify
   - Connect your GitHub repository
   - Configure build settings (if needed)

2. **Deploy**
   - Netlify will automatically deploy your site
   - Get a custom domain or use the provided Netlify URL

### Vercel

1. **Import Project**
   - Sign up for Vercel
   - Import your GitHub repository
   - Configure project settings
   - Deploy with one click

## 🐛 Troubleshooting

### Common Issues

1. **Images not loading**
   - Check file paths in HTML
   - Ensure images are in the correct folder
   - Verify file extensions and case sensitivity

2. **Dark mode not persisting**
   - Check if localStorage is enabled in browser
   - Clear browser cache and try again
   - Check JavaScript console for errors

3. **Animations not working**
   - Ensure AOS library is properly loaded
   - Check internet connection for CDN resources
   - Verify JavaScript is enabled in browser

4. **Mobile menu not working**
   - Check hamburger menu JavaScript event listeners
   - Verify CSS for mobile breakpoints
   - Test on actual mobile devices

### Browser Compatibility

The website supports:
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Guidelines

- Follow the existing code style
- Test on multiple devices and browsers
- Update documentation if needed
- Keep commits clean and descriptive

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

**Khushi Chauhan**
- Email: khushi.chauhan@example.com
- LinkedIn: linkedin.com/in/khushi-chauhan
- GitHub: github.com/khushi-chauhan
- Phone: +91 1234567890

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for the icon library
- [AOS](https://michalsnik.github.io/aos/) for the scroll animation library
- [Picsum](https://picsum.photos/) for placeholder images
- The open-source community for inspiration and resources

## 📈 Future Enhancements

- [ ] Blog CMS integration
- [ ] Project live demos
- [ ] Multi-language support
- [ ] Advanced analytics
- [ ] PWA functionality
- [ ] Backend integration for contact form
- [ ] Content management system
- [ ] Portfolio search functionality

---

**Made with ❤️ by Khushi Chauhan**

If you find this project helpful, please consider giving it a ⭐ on GitHub!

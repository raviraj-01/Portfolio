# Modern Portfolio Website

A beautiful, responsive portfolio website built with HTML, CSS, and JavaScript. Features smooth animations, modern design, and mobile-first approach.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🎯 Interactive elements and hover effects
- 📧 Contact form with validation
- 🚀 Fast loading and optimized performance
- 🎭 Typing effect animation
- 📊 Scroll-triggered animations
- 🌟 Parallax effects

## Sections

1. **Hero Section** - Introduction with animated typing effect
2. **About** - Personal bio and statistics
3. **Skills** - Technical skills organized by categories
4. **Projects** - Portfolio showcase with project details
5. **Contact** - Contact form and social links

## Customization Guide

### 1. Personal Information

**In `index.html`, update the following:**

- **Line 6**: Change page title
  ```html
  <title>Your Name - Portfolio</title>
  ```

- **Line 18**: Update navigation logo
  ```html
  <a href="#home">Your Name</a>
  ```

- **Line 33**: Update hero title
  ```html
  Hi, I'm <span class="highlight">Your Name</span>
  ```

- **Line 35**: Update professional title
  ```html
  <h2 class="hero-subtitle">Full Stack Developer</h2>
  ```

- **Line 36-40**: Update hero description
  ```html
  <p class="hero-description">
      Your personal description here...
  </p>
  ```

- **Line 46**: Update hero image
  ```html
  <img src="path/to/your/photo.jpg" alt="Your Name">
  ```

### 2. About Section

**Lines 58-70**: Update your bio and statistics
```html
<p>Your personal bio paragraph 1...</p>
<p>Your personal bio paragraph 2...</p>

<div class="stat">
    <h3>50+</h3>
    <p>Projects Completed</p>
</div>
<!-- Update other stats -->
```

### 3. Skills Section

**Lines 85-120**: Update your skills by category
```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-items">
        <span class="skill-item">Your Skill</span>
        <!-- Add more skills -->
    </div>
</div>
```

### 4. Projects Section

**Lines 135-220**: Update project information
```html
<div class="project-card">
    <div class="project-image">
        <img src="path/to/project/image.jpg" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="https://your-live-demo.com" class="project-link" target="_blank">
                    <i class="fas fa-external-link-alt"></i>
                </a>
                <a href="https://github.com/yourusername/repo" class="project-link" target="_blank">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
    </div>
</div>
```

### 5. Contact Information

**Lines 235-255**: Update contact details
```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-method">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
```

**Lines 257-272**: Update social media links
```html
<a href="https://linkedin.com/in/yourprofile" class="social-link" target="_blank">
    <i class="fab fa-linkedin"></i>
</a>
<a href="https://github.com/yourusername" class="social-link" target="_blank">
    <i class="fab fa-github"></i>
</a>
```

### 6. Typing Effect Animation

**In `script.js`, lines 175-180**: Customize the typing animation titles
```javascript
const titles = [
    'Your Title 1',
    'Your Title 2', 
    'Your Title 3',
    'Your Title 4'
];
```

### 7. Color Scheme

**In `styles.css`, update CSS custom properties for easy color changes:**

Main gradient colors (used throughout):
- `#667eea` (Primary blue)
- `#764ba2` (Primary purple)
- `#f093fb` (Accent pink)
- `#f5576c` (Accent red)

To change colors, find and replace these hex values throughout the CSS file.

### 8. Images

Replace placeholder images with your own:
- **Hero image**: 300x300px recommended
- **Project images**: 400x250px recommended
- Use high-quality images for best results

### 9. Fonts

The website uses Inter font from Google Fonts. To change:
1. Update the Google Fonts link in `index.html` (line 8)
2. Update the font-family in `styles.css` (line 12)

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. Optimize images before uploading
2. Use WebP format for better compression
3. Minify CSS and JavaScript for production
4. Consider using a CDN for faster loading

## Contact Form Setup

The contact form currently shows a success message without actually sending emails. To make it functional:

1. **Backend Integration**: Connect to a backend service (Node.js, PHP, etc.)
2. **Email Services**: Use services like EmailJS, Formspree, or Netlify Forms
3. **Serverless Functions**: Use Vercel Functions or Netlify Functions

### Example with EmailJS:

1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Add EmailJS SDK to your HTML
3. Update the form submission in `script.js`

## Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on every push

### Vercel
1. Import your GitHub repository to Vercel
2. Deploy with zero configuration

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing this portfolio, feel free to:
- Open an issue on GitHub
- Check the documentation
- Contact the developer

---

**Happy coding! 🚀**
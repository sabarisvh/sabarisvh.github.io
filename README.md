# 🌟 Academic Portfolio Website

A modern, responsive academic portfolio website built for GitHub Pages. This template provides a clean, professional design that showcases your research, publications, projects, and academic achievements effectively.

![Portfolio Preview](https://img.shields.io/badge/Status-Ready%20to%20Deploy-brightgreen)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Compatible-blue)
![Responsive](https://img.shields.io/badge/Design-Responsive-orange)

## ✨ Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Fully Responsive**: Looks great on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, mobile menu, typing effects
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript for performance
- **Accessibility**: WCAG compliant with keyboard navigation support

## 🚀 Quick Start

### 1. Fork or Clone This Repository

```bash
git clone https://github.com/sabarisvh/sabarisvh.github.io.git
cd sabarisvh.github.io
```

### 2. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

Your website will be available at: `https://sabarisvh.github.io`

### 3. Customize Your Content

Edit the following files to personalize your website:

#### `index.html`
- Replace "Your Name" with your actual name
- Update the hero section with your information
- Modify the about section with your story
- Add your real projects in the projects section
- Update contact information
- Add your actual social media links

#### `styles.css`
- Change color scheme by modifying CSS variables in `:root`
- Adjust fonts, spacing, or layout as needed
- Customize animations and transitions

#### `script.js`
- Modify the typing effect roles in `initTypingEffect()` function
- Customize form submission behavior
- Add any additional interactive features

## 🎨 Customization Guide

### Changing Colors

The website uses CSS custom properties for easy theming. Update these variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;     /* Main brand color */
    --primary-dark: #4f46e5;      /* Darker shade */
    --secondary-color: #f59e0b;   /* Accent color */
    --text-color: #1f2937;        /* Main text */
    --text-light: #6b7280;        /* Secondary text */
    --bg-color: #ffffff;          /* Background */
    --bg-section: #f9fafb;        /* Section backgrounds */
}
```

### Adding Your Photo

Replace the placeholder avatar icons with your actual photos:

1. Add your photos to the repository
2. Update the hero and about sections in `index.html`:

```html
<!-- Replace the icon with an image -->
<div class="hero-avatar">
    <img src="your-photo.jpg" alt="Your Name">
</div>
```

3. Add corresponding CSS styles for the image.

### Updating Projects

Replace the example projects with your real work:

```html
<div class="project-card">
    <div class="project-image">
        <img src="project-screenshot.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="https://your-project-demo.com" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

### Contact Form Setup

The contact form includes client-side validation but needs backend integration for actual email sending. Options include:

1. **Formspree**: Add `action="https://formspree.io/f/your-form-id"` to the form
2. **Netlify Forms**: If hosting on Netlify, add `netlify` attribute to the form
3. **EmailJS**: Integrate EmailJS for client-side email sending
4. **Custom Backend**: Build your own API endpoint

Example with Formspree:

```html
<form class="contact-form" id="contact-form" action="https://formspree.io/f/your-form-id" method="POST">
    <!-- form fields -->
</form>
```

Your GitHub repository should be named `sabarisvh.github.io` for automatic GitHub Pages deployment.

## 📱 Responsive Breakpoints

The website is designed mobile-first with the following breakpoints:

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 Development

### Local Development

1. Clone the repository
2. Open `index.html` in your browser, or
3. Use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Visit `http://localhost:8000` to view your site.

### File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── assets/             # Images and other assets (create as needed)
    ├── images/
    └── icons/
```

## 🎯 SEO Optimization

The template includes several SEO best practices:

- Semantic HTML5 structure
- Meta descriptions and title tags
- Open Graph tags for social sharing
- Structured data markup
- Fast loading optimized code

To further improve SEO:

1. Add a `sitemap.xml` file
2. Include `robots.txt`
3. Add Open Graph and Twitter Card meta tags
4. Optimize images with alt text
5. Use Google Analytics or similar tracking

## 🌐 Browser Support

This website supports all modern browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/sabarisvh/sabarisvh.github.io/issues).

## 💡 Tips for Success

1. **Keep it updated**: Regularly update your projects and skills
2. **Show your personality**: Let your unique voice shine through
3. **Quality over quantity**: Better to have fewer, well-documented projects
4. **Mobile-first**: Always test on mobile devices
5. **Performance matters**: Keep images optimized and code clean
6. **Tell a story**: Your portfolio should tell the story of your journey

## 📞 Support

If you have any questions or need help customizing your portfolio, feel free to:

- Open an issue on GitHub
- Contact me through the portfolio contact form
- Connect with me on social media

---

**Happy coding! 🚀**

Remember to star ⭐ this repository if you found it helpful!
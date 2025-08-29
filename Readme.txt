# Michael Asante OFOSU - Portfolio Website

A professional portfolio website showcasing research expertise in Statistics, Data Science, Machine Learning, and Artificial Intelligence.

## 🎯 Overview

This website serves as a comprehensive portfolio for Michael Asante OFOSU, a PhD Statistics and Data Science student at Auburn University. It highlights research projects, publications, technical skills, and professional experience in statistical modeling, machine learning, and responsible AI development.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Interactive Portfolio**: Filterable research project showcase with detailed project pages
- **Publications Section**: Dynamic carousel displaying research papers and working papers
- **Skills Visualization**: Animated progress bars showing technical proficiency levels
- **Contact Forms**: Working contact form for research collaboration inquiries
- **Social Integration**: Links to LinkedIn, GitHub, and academic profiles
- **Research Resources**: Dedicated page for educational materials and tutorials

## 🛠 Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Framework**: Bootstrap 5.3.3
- **Icons**: Bootstrap Icons
- **Animations**: AOS (Animate On Scroll)
- **Image Gallery**: GLightbox
- **Carousels**: Swiper.js
- **Animations**: Typed.js for text animation
- **Counters**: PureCounter for statistics

## 📁 Project Structure

```
portfolio-website/
├── index.html                 # Main homepage
├── portfolio-details.html     # Research project details
├── service-details.html       # Expertise areas details
├── starter-page.html          # Research resources page
├── README.md                  # Project documentation
├── assets/
│   ├── css/
│   │   └── main.css          # Main stylesheet
│   ├── js/
│   │   └── main.js           # Main JavaScript file
│   ├── img/                  # Image assets
│   │   ├── my-profile-img.jpg
│   │   ├── hero-bg.jpg
│   │   ├── services.jpg
│   │   └── portfolio/        # Research project images
│   └── vendor/               # Third-party libraries
│       ├── bootstrap/
│       ├── bootstrap-icons/
│       ├── aos/
│       ├── glightbox/
│       ├── swiper/
│       ├── typed.js/
│       └── purecounter/
└── forms/
    └── contact.php           # Contact form handler (requires PHP)
```

## 🚀 Quick Start

1. **Clone or Download** the project files to your local machine
2. **Open** `index.html` in your preferred code editor
3. **Customize** the content with your information
4. **Replace** images in the `assets/img/` folder
5. **Test** by opening `index.html` in a web browser

## 🎨 Customization Guide

### Personal Information

**Update contact details in all HTML files:**
```html
<!-- Phone number -->
<p>+1(334)-870-5290</p>

<!-- Email addresses -->
<p>mike.ofosu16@gmail.com<br>mao0049@auburn.edu</p>

<!-- Social media links -->
<a href="https://linkedin.com/in/michael-ofosu" target="_blank">
<a href="https://github.com/maofosu1" target="_blank">
```

### Images

**Replace these key images:**
- `assets/img/my-profile-img.jpg` (300x300px) - Profile photo
- `assets/img/hero-bg.jpg` (1920x1080px) - Homepage background
- `assets/img/services.jpg` (800x600px) - Services page background
- `assets/img/portfolio/*.jpg` (600x400px) - Research project images

### Content Sections

**Homepage sections to customize:**
- Hero section: Name and typed animation roles
- About section: Professional summary and details
- Skills section: Technical proficiencies and percentages
- Resume section: Education, experience, and awards
- Research portfolio: Project descriptions and categories
- Publications: Research papers and working papers

### Statistics Counter

**Update the stats in the homepage:**
```html
<span data-purecounter-end="6" class="purecounter"></span> <!-- Publications -->
<span data-purecounter-end="250" class="purecounter"></span> <!-- Students mentored -->
<span data-purecounter-end="3" class="purecounter"></span> <!-- Awards -->
```

### Navigation Menu

**Modify navigation items in all HTML files:**
```html
<nav id="navmenu" class="navmenu">
  <ul>
    <li><a href="#hero">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#resume">Resume</a></li>
    <!-- Add or modify menu items here -->
  </ul>
</nav>
```

## 📱 Responsive Design

The website is fully responsive and tested on:
- Desktop (1920px and above)
- Laptop (1024px - 1919px)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## 🔧 Development Setup

### Using VS Code (Recommended)

1. **Install Extensions:**
   - Live Server
   - Auto Rename Tag
   - Image Preview

2. **Local Development:**
   - Open project folder in VS Code
   - Right-click `index.html` → "Open with Live Server"
   - Browser will auto-refresh on file changes

### Using Other Editors

1. Open `index.html` directly in any web browser
2. Use browser developer tools for debugging
3. Refresh browser (Ctrl+F5) after making changes

## 🚀 Deployment Options

### Netlify (Recommended)
1. Create account at [netlify.com](https://netlify.com)
2. Drag project folder to Netlify dashboard
3. Configure custom domain if desired
4. Auto-deploy on file changes

### GitHub Pages
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main`)
4. Access via `username.github.io/repository-name`

### Traditional Web Hosting
1. Upload files via FTP/File Manager
2. Ensure PHP support for contact forms
3. Configure SSL certificate
4. Set up custom domain

## 📧 Contact Form Setup

The contact form requires PHP support. Update `forms/contact.php`:

```php
<?php
$receiving_email_address = 'your-email@domain.com';
// Configure email settings
?>
```

**Alternative solutions:**
- Netlify Forms (add `netlify` attribute to form)
- Formspree.io integration
- EmailJS for client-side email handling

## 🎯 SEO Optimization

**Update meta tags in each HTML file:**
```html
<title>Your Name - Professional Title</title>
<meta name="description" content="Your professional description">
<meta name="keywords" content="your, relevant, keywords">
```

**Add Google Analytics:**
```html
<!-- Add before closing </head> tag -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
```

## 🔍 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project uses the iPortfolio Bootstrap template:
- Template: [iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/)
- License: [BootstrapMade License](https://bootstrapmade.com/license/)

## 🤝 Contributing

To contribute to this project:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

For questions or issues:
- **Email**: mike.ofosu16@gmail.com
- **Auburn Email**: mao0049@auburn.edu
- **LinkedIn**: [linkedin.com/in/michael-ofosu](https://linkedin.com/in/michael-ofosu)
- **GitHub**: [github.com/maofosu1](https://github.com/maofosu1)

## 🎓 Research Focus Areas

- Machine Learning & Responsible AI
- Complex Systems Analysis
- Health Informatics
- Time Series Analysis
- Statistical Modeling
- Academic Teaching & Mentoring

---

**Last Updated**: August 2025
**Version**: 1.0.0
**Author**: Michael Asante OFOSU
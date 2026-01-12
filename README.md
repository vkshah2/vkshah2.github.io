# 🌐 Vinit's Personal Website

Welcome to the repository for my personal website! This is my digital space where I share my thoughts, curate interesting resources, and connect with others.

[![Live Site](https://img.shields.io/badge/Live-vkshah2.github.io-brown?style=for-the-badge)](https://vkshah2.github.io)
[![Blog](https://img.shields.io/badge/Blog-vkshah2.blogspot.com-orange?style=for-the-badge)](https://vkshah2.blogspot.com)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-blue?style=for-the-badge&logo=github)](https://pages.github.com/)

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Pages](#pages)
- [Tech Stack](#tech-stack)
- [Setup & Development](#setup--development)
- [File Structure](#file-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## 🎯 About

This is my personal website where I:

- Share curated resources and interesting finds
- Write about various topics on [my blog](https://vkshah2.blogspot.com)
- Document my interests and discoveries
- Connect with others who share similar interests

**Note:** My blog is hosted separately on [Blogspot](https://vkshah2.blogspot.com) for better content management and features.

## ✨ Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Accessible**: Built with accessibility in mind (WCAG compliant)
- **Fast & Lightweight**: Static site with minimal dependencies
- **SEO Optimized**: Meta tags and semantic HTML for better visibility
- **Modern UI**: Clean, minimalist design with smooth animations
- **Warm Color Scheme**: Pleasant brownish tones that are easy on the eyes

### User Experience Features

- 🎯 Sticky navigation
- 🔝 Back-to-top button
- 📱 Mobile-friendly menu
- ⌨️ Keyboard navigation support
- 🎨 Smooth animations and transitions
- 🔍 SEO and Open Graph tags

## 📄 Pages

### 🏠 Home (`index.html`)

The landing page featuring an introduction and quick links to other sections.

### 📝 Blog (External)

My blog is hosted on [Blogspot](https://vkshah2.blogspot.com) where I write about various topics that interest me.

### 🔗 Resources (`links.html`)

A curated collection of useful resources, tools, and interesting links organized by category.

### 👤 About (`about.html`)

Information about me, my interests, and how to get in touch.

### 🚫 404 (`404.html`)

Custom error page for better user experience.

## 🛠️ Tech Stack

This website is built with simple web technologies:

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Vanilla JS for interactivity
- **GitHub Pages**: Free hosting
- **Blogspot**: Blog hosting platform

Clean, straightforward code with no complex frameworks or build tools.

## 🚀 Setup & Development

### Prerequisites

- A web browser
- A text editor (VS Code recommended)
- Git (optional, for version control)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/vkshah2/vkshah2.github.io.git
   cd vkshah2.github.io
   ```

2. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. **Make changes**
   - Edit HTML, CSS, or JavaScript files
   - Refresh browser to see changes

## 📁 File Structure

```
vkshah2.github.io/
├── index.html          # Homepage
├── links.html          # Resources page
├── about.html          # About page
├── 404.html            # Error page
├── styles.css          # Shared styles
├── main.js             # Shared JavaScript
├── robots.txt          # Search engine instructions
└── README.md           # This file
```

## 🎨 Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary: #92400e;       /* Main brown color */
    --primary-dark: #78350f;  /* Darker brown for hover */
    --accent: #d97706;        /* Accent orange */
    --text-primary: #1c1917;  /* Dark text */
    --text-secondary: #57534e; /* Gray text */
    --bg-primary: #fafaf9;    /* Page background */
    --bg-secondary: #fef3c7;  /* Card backgrounds */
    --border: #e7e5e4;        /* Border color */
}
```

### Content

1. **Update personal information**:
   - Name in navigation and footer
   - About page content
   - Social media links

2. **Customize resources**:
   - Edit `links.html`
   - Add your favorite resources and tools

### Adding New Pages

1. Create a new HTML file
2. Copy the navigation and footer from existing pages
3. Add link to navigation menu
4. Update all other pages' navigation

## 🌐 Deployment

This site is automatically deployed via GitHub Pages.

### Steps to Deploy:

1. **Enable GitHub Pages**:
   - Go to repository Settings
   - Navigate to "Pages" section
   - Select "main" branch as source
   - Click Save

2. **Push changes**:
   ```bash
   git add .
   git commit -m "Update website"
   git push origin main
   ```

3. **Wait a few minutes** for changes to go live at `https://vkshah2.github.io`

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings

## 🤝 Contributing

This is a personal website, but suggestions are welcome!

- 🐛 Found a bug? Open an issue
- 💡 Have a suggestion? Open an issue
- 🔧 Want to contribute? Fork and create a pull request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

Feel free to use this as a template for your own personal website!

## 📬 Contact

- **Email**: [vkshah2@gmail.com](mailto:vkshah2@gmail.com)
- **GitHub**: [@vkshah2](https://github.com/vkshah2)
- **Twitter/X**: [@vkshah2](https://x.com/vkshah2)
- **Blog**: [vkshah2.blogspot.com](https://vkshah2.blogspot.com)

## 📝 Note

The site is not intended for search engine indexing (`robots.txt` + meta tags).

---

⭐ If you found this helpful, consider giving it a star!

Built with ❤️ by Vinit K Shah

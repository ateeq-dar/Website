<p align="center">
  <a href="https://ateeqportfolio.netlify.app/"><img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=15,10,25&height=250&section=header&text=Portfolio%20Website&fontSize=60&fontColor=ffffff&animation=twinkling&desc=With%20Intractive%20And%20UI%20&descSize=20&descAlignY=75&fontAlignY=40" width="100%" alt="Header" /></a><br>
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=8B5CF6&center=true&vCenter=true&width=600&lines=⚡+HTML;⚙️+CSS+%7C+JavaScript;🚀+Click+the+Preview+Button+Below!" alt="Tech Stack Animation" /><br><br>
  <a href="https://ateeqportfolio.netlify.app/"><img src="https://img.shields.io/badge/🚀_CLICK_HERE_FOR_LIVE_PREVIEW-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white" width="400" alt="Live Preview" /></a>
</p>
<hr>

# DAR Portfolio

A modern, responsive personal portfolio website showcasing professional experience, skills, and projects with an elegant dark theme and interactive design.

## 🌟 Features

- **Responsive Design** - Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern Dark Theme** - Professional dark interface with red accent colors and smooth gradients
- **Interactive Navigation** - Smooth scrolling navigation with mobile menu toggle
- **Hero Section** - Eye-catching introduction with custom cursor and animated background
- **About Section** - Professional background and introduction
- **Skills Showcase** - Display of technical expertise and competencies
- **Project Portfolio** - Gallery of featured projects with descriptions
- **Contact Form** - Functional contact section for visitor inquiries
- **Font Awesome Icons** - Comprehensive icon library for visual enhancement
- **Custom Styling** - Professional fonts (Rajdhani & Orbitron) with carefully curated color scheme
- **No Cache Headers** - Ensures fresh content delivery without browser caching issues

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with CSS variables and gradients
- **JavaScript** - Interactive features and functionality
- **Font Awesome 6.4.0** - Icon library
- **Google Fonts** - Typography (Rajdhani & Orbitron)

## 📂 Project Structure

```
Website/
├── index.html          # Main HTML file with all content
├── assets/
│   └── images/         # Image assets and logos
├── README.md           # This file
└── .git/               # Version control
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- No server installation required - works directly in browsers

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ateeq-dar/Website.git
cd Website
```

2. Open the website:
   - Simply double-click `index.html` to open in your default browser, or
   - Use a local server (recommended):

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## 📖 Usage

### Navigating the Site

- **Home** - Click the logo or "Home" in navigation to return to the hero section
- **About** - Learn about professional background and experience
- **Skills** - View technical competencies and expertise
- **Projects** - Explore featured work and accomplishments
- **Contact** - Fill out the contact form to get in touch

### Mobile Navigation

On mobile devices, use the menu toggle (☰) icon in the top-right corner to open/close the navigation menu.

## 🎨 Customization

### Colors

Edit the CSS variables in the `<style>` section of `index.html`:

```css
:root {
    --primary: #e63946;        /* Main accent color */
    --secondary: #ff2a3c;      /* Secondary accent */
    --dark: #0a0a0a;          /* Dark background */
    --darker: #050505;        /* Darker background */
    --light: #f1faee;         /* Light text */
    --gray: #1a1a1a;          /* Gray elements */
    --card-bg: rgba(20, 20, 20, 0.8);  /* Card background */
    --glow: 0 0 15px rgba(230, 57, 70, 0.7);  /* Glow effect */
}
```

### Fonts

The site uses two Google Fonts:
- **Rajdhani** - Primary font for body text
- **Orbitron** - Display font for headings

Modify the font weights or change fonts in the `<link>` tag within the `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@300;400;500;600;700&family=Orbitron:wght@400;500;600;700&display=swap" rel="stylesheet">
```

### Adding Images

Place image files in the `assets/images/` folder and reference them in the HTML:
```html
<img src="assets/images/your-image.jpg" alt="Description">
```

### Updating Content

- Search for section IDs (`#about`, `#skills`, `#projects`, etc.) in `index.html`
- Update text, links, and information as needed
- Add or remove portfolio items in the projects section

## 🔧 Favicon Setup

The portfolio includes three favicon formats for best compatibility:
- `assets/images/logo.svg` - Vector format
- `assets/images/logo.ico` - Icon format
- `assets/images/logo.png` - PNG format
- `assets/images/dar_logo.svg` - Custom SVG logo

Replace these files with your own branding assets.

## 💡 Tips

- **Browser Compatibility** - Test on multiple browsers for optimal experience
- **Mobile Testing** - Use browser DevTools to test responsive behavior
- **Performance** - Optimize large images before adding to the assets folder
- **Accessibility** - Ensure alt text is provided for all images
- **SEO** - Update meta tags and title for search engine optimization

## 📝 Sections Overview

| Section | Purpose | Key Elements |
|---------|---------|--------------|
| Hero | First impression | Title, tagline, animated background |
| About | Professional intro | Background, experience summary |
| Skills | Expertise display | Technical skills, competencies |
| Projects | Work portfolio | Project descriptions, links |
| Contact | Communication | Contact form, inquiry handling |

## 🌐 Deployment

This portfolio can be deployed to:

- **GitHub Pages** - Free hosting directly from GitHub
- **Netlify** - Drag-and-drop deployment
- **Vercel** - Modern hosting platform
- **Traditional Web Hosting** - Upload files to any web server
- **Cloudflare Pages** - Static site hosting

## 📧 Contact & Support

For questions or suggestions regarding this portfolio:
- **GitHub** - [ateeq-dar](https://github.com/ateeq-dar)
- **Email** - Add your contact information to the contact section

## 📄 License

This project is open source and available for personal use and modification. Feel free to customize and deploy as needed.

## 🙌 Acknowledgments

- Font Awesome for the icon library
- Google Fonts for typography
- Modern CSS techniques for responsive design

---

**Last Updated:** February 2026  
**Status:** Active Development

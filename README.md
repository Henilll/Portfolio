# 🎨 Henil Bhavsar - Portfolio

A modern, responsive portfolio website showcasing my work as a Junior Python Developer and AI/ML Enthusiast. Built with clean design principles and smooth animations.

## 🌐 Live Demo

**[Visit Portfolio →](https://henil-portfolio.netlify.app/)**

## ✨ Features

- **Modern Dark Theme** - Professional color palette with cyan accents
- **Fully Responsive** - Optimized for all device sizes
- **Smooth Animations** - Engaging hover effects and transitions
- **JSON-Powered** - Easy content management through a single data object
- **Fast Loading** - Optimized performance with no external dependencies
- **Clean UI/UX** - Intuitive navigation with smooth scrolling

## 🎯 Sections

1. **Home** - Hero section with introduction and call-to-action buttons
2. **Profile Summary** - Professional overview and career objectives
3. **Skills** - Technical skills organized by category (AI/ML, Backend, Frontend, Databases, DevOps, Libraries)
4. **Experience** - Work experience with company details and skills utilized
5. **Projects** - 9 featured projects with descriptions, technologies, and live links
6. **Certifications** - Professional certifications from IBM, AWS, and Johns Hopkins
7. **Contact** - Multiple contact methods and social media links

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with gradients, animations, and flexbox/grid layouts
- **JavaScript (ES6)** - Dynamic content rendering from JSON data
- **Google Fonts** - Space Grotesk & Inter typefaces
- **Responsive Design** - Mobile-first approach

## 🎨 Design System

### Color Palette
- Background: `#0B0F19`
- Primary Text: `#E5E7EB`
- Secondary Text: `#9CA3AF`
- Accent Color: `#38BDF8`
- Card Background: `#111827`

### Typography
- Headings: **Space Grotesk** (Medium/Bold)
- Body: **Inter** (Regular/Medium)

## 📁 Project Structure

```
portfolio/
│
├── index.html              # Main HTML file with embedded CSS and JS
│
└── README.md              # Documentation
```

## 🚀 Quick Start

### Option 1: Direct Use
1. Download the `index.html` file
2. Open it in any modern web browser
3. Done! No build process required

### Option 2: Local Development
```bash
# Clone or download the repository
git clone <your-repo-url>

# Navigate to project folder
cd portfolio

# Open in browser
open index.html
```

### Option 3: Deploy to Netlify
1. Push code to GitHub repository
2. Connect repository to Netlify
3. Deploy with one click
4. Your portfolio is live!

## ✏️ Customization Guide

All content is managed through the `portfolioData` object in the JavaScript section. Here's how to update different sections:

### Update Personal Info
```javascript
hero: {
    name: "Your Name",
    subtitle: "Your Title",
    description: "Your description",
    // ...
}
```

### Add a New Project
```javascript
projects: [
    {
        title: "Project Name",
        description: "Project description",
        image: "image-url",
        technologies: ["Tech1", "Tech2"],
        link: "project-url"
    },
    // Add more projects here
]
```

### Add a New Skill Category
```javascript
skills: [
    {
        category: "Category Name",
        items: ["Skill1", "Skill2", "Skill3"]
    },
    // Add more categories here
]
```

### Add Experience
```javascript
experience: [
    {
        title: "Job Title",
        company: "Company Name",
        location: "Location",
        startDate: "Start Date",
        endDate: "End Date",
        skills: ["Skill1", "Skill2"]
    }
]
```

### Add Certification
```javascript
certifications: [
    {
        title: "Certification Name",
        issuer: "Organization",
        date: "Month Year"
    }
]
```

### Update Contact Info
```javascript
contact: [
    { icon: "📧", label: "Email", value: "your-email@example.com" },
    { icon: "📱", label: "Phone", value: "+1234567890" },
    { icon: "📍", label: "Location", value: "Your City, Country" }
]
```

### Update Social Links
```javascript
social: [
    { icon: "💻", name: "GitHub", url: "github-url" },
    { icon: "👔", name: "LinkedIn", url: "linkedin-url" },
    // Add more social links
]
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Performance

- ✅ No external dependencies (except Google Fonts)
- ✅ Minimal JavaScript - vanilla JS only
- ✅ Optimized images loaded from CDN
- ✅ CSS animations using GPU acceleration
- ✅ Semantic HTML for better SEO

## 🌟 Key Features Explained

### JSON-Based Content Management
All portfolio content is stored in a single `portfolioData` object, making updates incredibly easy. No need to touch HTML or CSS - just update the JSON data.

### Smooth Scrolling
Navigation links use smooth scrolling behavior for better user experience.

### Custom Scrollbar
Styled scrollbar matching the portfolio's color scheme (cyan on dark background).

### Hover Effects
- Cards lift up on hover
- Links change color
- Buttons have scale animations
- Smooth color transitions

## 📄 License

This project is open source and available for personal and commercial use.

## 👤 Contact

**Henil Bhavsar**
- Email: henilbhavsar164@gmail.com
- Phone: +91 9714033439
- Location: Ahmedabad, Gujarat, India
- Portfolio: [henil-portfolio.netlify.app](https://henil-portfolio.netlify.app/)

## 🔗 Connect With Me

- [GitHub](https://github.com/Henilll)
- [LinkedIn](https://www.linkedin.com/in/henil-bhavsar-18b45b311)
- [Twitter/X](https://x.com/Henil_164)
- [Instagram](https://www.instagram.com/_henil_.04)

## 🙏 Acknowledgments

- Google Fonts for typography
- Netlify for hosting
- Inspiration from modern portfolio designs
fdf
---

**Made with ❤️ by Henil Bhavsar**

*Last Updated: January 2026*

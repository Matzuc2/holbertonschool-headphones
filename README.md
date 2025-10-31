# 🎧 Headphones Website

A responsive, modern website for headphones built with HTML5 and CSS3, featuring custom icon fonts and mobile-first design principles.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Development Process](#development-process)
- [Custom Icons](#custom-icons)
- [Responsive Design](#responsive-design)
- [Browser Support](#browser-support)
- [Contributing](#contributing)

## 🎯 Overview

This project is a complete responsive website for a headphones company, built as part of the Holberton School curriculum. The website showcases modern web development practices with a focus on responsive design, accessibility, and performance.

## ✨ Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Custom Icon Font** - Integrated Holberton School custom icon font with 21+ glyphs
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Modern CSS** - Flexbox layouts, CSS Grid, and advanced styling techniques
- **Contact Form** - Interactive contact section with custom styling
- **Performance Optimized** - Lightweight and fast-loading

## 🛠 Technologies Used

- **HTML5** - Semantic markup and modern structure
- **CSS3** - Advanced styling with Flexbox and Grid
- **Custom Icon Font** - IcoMoon generated font (`holberton_school-icon`)
- **Google Fonts** - Source Sans Pro font family
- **Responsive Design** - Mobile-first approach with media queries

## 📁 Project Structure

```
holbertonschool-headphones/
├── 0-index.html          # Basic hero section
├── 1-index.html          # Hero + What We Do section
├── 2-index.html          # Hero + What We Do + Our Results
├── 3-index.html          # Hero + What We Do + Our Results + Contact
├── 4-index.html          # Complete website with footer
├── 00-styles.css         # Styles for 0-index.html
├── 01-styles.css         # Styles for 1-index.html
├── 02-styles.css         # Styles for 2-index.html
├── 03-styles.css         # Styles for 3-index.html
├── 04-styles.css         # Styles for 4-index.html (complete)
├── README.md
└── images/
    ├── headphones_hero_1.jpg
    ├── headphones_hero_2.jpg
    ├── logo_headphones.png
    ├── pentagone.png
    ├── social_icons.png
    └── holberton_school-icon/
        ├── style.css         # Icon font CSS
        ├── style.scss        # Icon font SCSS
        ├── variables.scss    # SCSS variables
        ├── demo.html         # Icon preview
        ├── selection.json    # IcoMoon project file
        └── fonts/           # Font files
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/holbertonschool-headphones.git
   cd holbertonschool-headphones
   ```

2. **Open in browser**
   - Open any of the HTML files directly in your browser
   - For the complete experience, open `4-index.html`

3. **Development server** (optional)
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

## 🔄 Development Process

The project was built incrementally with each stage adding new sections:

### Stage 0: Hero Section
- Header with logo and navigation
- Hero background with call-to-action
- Mobile hamburger menu

### Stage 1: What We Do Section
- Custom icon integration
- Service descriptions
- Responsive grid layout

### Stage 2: Our Results Section
- Pentagon-shaped result indicators
- Background image overlay
- Statistical data display

### Stage 3: Contact Section
- Custom form styling
- Input field animations
- Responsive form layout

### Stage 4: Footer Section
- Social media icons
- Logo placement
- Copyright information

## 🎨 Custom Icons

The project uses a custom icon font generated with IcoMoon, featuring:

- **21 custom icons** including arrows, social media, and utility icons
- **Scalable vector graphics** that work at any size
- **CSS integration** with easy-to-use class names

### Available Icons:
- `holberton_school-icon-ic_sound` - Audio/Sound
- `holberton_school-icon-ic_video` - Video
- `holberton_school-icon-ic_music` - Music
- `holberton_school-icon-ic_hearing` - Hearing/Listening
- `holberton_school-icon-ic_facebook` - Facebook
- `holberton_school-icon-ic_twitter` - Twitter
- `holberton_school-icon-ic_instagram` - Instagram
- And many more...

### Usage Example:
```html
<span class="holberton_school-icon-ic_sound"></span>
```

```css
.holberton_school-icon-ic_sound {
    font-size: 48px;
    color: #FF6565;
}
```

## 📱 Responsive Design

The website is built with a mobile-first approach featuring:

### Breakpoints:
- **Mobile**: ≤ 480px
- **Tablet**: 481px - 767px  
- **Desktop**: ≥ 768px

### Key Responsive Features:
- Flexible grid layouts that adapt to screen size
- Mobile hamburger navigation menu
- Scalable typography and spacing
- Touch-friendly interactive elements
- Optimized images for different screen densities

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- IE 11+ (with fallbacks)

## 🎨 Design Highlights

### Color Palette:
- **Primary Red**: `#FF6565`
- **Dark Text**: `#071629`
- **White**: `#FFFFFF`
- **Black**: `#000000`

### Typography:
- **Font Family**: Source Sans Pro
- **Weights**: 200, 300, 400, 600, 700, 900

### Key CSS Features:
- Flexbox and CSS Grid layouts
- CSS custom properties (variables)
- Advanced selectors and pseudo-elements
- Smooth transitions and hover effects
- Box shadows and modern styling

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📚 Learning Objectives

This project demonstrates proficiency in:

- **HTML5 semantic structure** and accessibility
- **Advanced CSS techniques** including Flexbox and Grid
- **Responsive web design** principles
- **Custom font integration** and icon usage
- **Mobile-first development** approach
- **Cross-browser compatibility**
- **Performance optimization**

## 📄 License

This project is part of the Holberton School curriculum and is for educational purposes.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)

---

**Made with ❤️ at Holberton School**
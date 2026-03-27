# Meganandhitha K - Portfolio Website

A world-class, award-worthy portfolio website built with **pure HTML, CSS, and JavaScript**—no frameworks, no libraries, just pure modern web standards.

## 🎨 Design Philosophy

This portfolio embodies a **brutalist-meets-futuristic** aesthetic with:
- Deep space black (#050508) as the canvas
- Electric violet (#8b5cf6) for primary interactions
- Neon mint (#10b981) for accents
- Glassmorphism and asymmetric layouts
- Clean, intentional design at every pixel

**Typography**
- **Headings**: Space Grotesk (bold, technical feel)
- **Body**: Inter (readable, modern)

## 📋 Features

### ✨ Hero Section
- Full viewport height with animated star constellation background
- Glitch text animation on the main heading
- Typewriter cycling effect for role titles
- Floating skill badges
- Dual CTA buttons (View Work / Connect on LinkedIn)
- Animated scroll indicator

### 👤 About Section
- Asymmetric 2-column layout
- Fake code block (Python snippet) showing skills
- Bio text with college details
- Animated number counters for projects, certifications, and languages

### 🛠️ Skills Section
- Bento-grid layout with 4 skill categories
- Languages: Python, C, Java, SQL
- Web & Cloud: HTML/CSS/JS, AWS, Azure, Google Cloud AI
- Specialized Tools: UiPath RPA, Power BI, MATLAB, Excel
- Soft Skills: Problem Solving, Teamwork, Leadership, Communication
- Hover animations with glow effects
- Dot-based skill level indicators

### 💼 Projects Section
- Featured project cards with image placeholders
- Project 1: **Travel Buddy** (RPA Automation) - UiPath, Excel, Outlook
- Project 2: **Fashion Store Analytics Dashboard** - Power BI, Excel
- Tech stack pills, descriptions, tags, and case study buttons
- Animated borders on hover

### 🏆 Certifications Section
- 13+ professional certifications in masonry grid
- Card-flip animation on click to reveal descriptions
- Organized by category: Cloud, AI, Programming, DevOps, Security, etc.
- Issuer details and learning outcomes

### 🔗 Digital Presence Section
- 4 social media cards with neon borders
- GitHub, LinkedIn, LeetCode, HackerRank
- Direct links to all platforms
- Hover glow effects

### 📞 Contact Section
- Frosted glass card design
- Contact information (location, phone, email)
- Pulsing badge for availability
- Motivational quote

### 🧭 Navigation
- Sticky navbar with MK monogram logo
- Active link highlighting on scroll
- Responsive hamburger menu for mobile
- Smooth scroll-to-section behavior

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required—just open the HTML file

### Installation

1. **Open in Browser**
   ```
   Simply double-click index.html or drag it into your browser
   ```

2. **Development Server (Optional)**
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js
   npx http-server
   ```

3. **Visit**
   ```
   http://localhost:8000
   ```

## 🎯 Customization Guide

### Changing Personal Information

**Name & Title**
```html
<!-- Line ~640 in Hero Section -->
<h1 class="hero-name">
    Your Name
    <span>K</span>
</h1>
```

**About Bio**
```html
<!-- Line ~960 in About Section -->
<p>
    Your bio text here...
</p>
```

**Contact Details**
```html
<!-- Line ~1400 in Contact Section -->
<div class="contact-row">
    📍 Your City, State
</div>
<div class="contact-row">
    📞 Your Phone
</div>
<div class="contact-row">
    ✉ your.email@example.com
</div>
```

### Updating Social Links

```html
<!-- Line ~1350 in Digital Presence Section -->
<a href="https://github.com/YourUsername" target="_blank" class="presence-btn">Visit →</a>
<a href="https://linkedin.com/in/yourprofile" target="_blank" class="presence-btn">Visit →</a>
```

### Modifying Skills

```html
<!-- In Skills Section (~890) -->
<div class="skill-card">
    <div class="skill-icon">🐍</div>
    <div class="skill-name">Your Skill</div>
    <div class="skill-level">
        <div class="dot active"></div>
        <div class="dot active"></div>
        <div class="dot active"></div>
        <div class="dot"></div>
        <div class="dot"></div>
    </div>
</div>
```

### Updating Projects

```html
<!-- In Projects Section (~1040) -->
<div class="project-card fade-in">
    <div class="project-image">🎨</div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <div class="project-tech">
            <div class="tech-pill">Technology 1</div>
            <div class="tech-pill">Technology 2</div>
        </div>
        <p class="project-description">
            Your project description...
        </p>
        <div class="project-tags">
            <span class="tag">#Tag1</span>
            <span class="tag">#Tag2</span>
        </div>
        <a href="#" class="project-cta">Case Study →</a>
    </div>
</div>
```

### Updating Certifications

```html
<!-- In Certifications Section (~1180) -->
<div class="cert-card fade-in">
    <div class="cert-card-front">
        <div class="cert-icon">🎓</div>
        <div class="cert-name">Certification Name</div>
        <div class="cert-tag">Category</div>
    </div>
    <div class="cert-card-back">
        <div class="cert-description">What you learned...</div>
    </div>
</div>
```

### Changing Colors

Edit the CSS variables at the top of the style section:

```css
:root {
    --color-black: #050508;      /* Main background */
    --color-violet: #8b5cf6;     /* Primary accent */
    --color-mint: #10b981;       /* Secondary accent */
    --color-white: #f1f5f9;      /* Text color */
    --color-slate: #334155;      /* Muted text */
    --color-dark-slate: #1e293b; /* Darker backgrounds */
}
```

### Adjusting Spacing

```css
:root {
    --spacing-xs: 0.5rem;
    --spacing-sm: 1rem;
    --spacing-md: 2rem;
    --spacing-lg: 3rem;
    --spacing-xl: 4rem;
}
```

## 🎬 Interactive Features

### Custom Cursor
- Desktop only (hidden on mobile)
- Violet dot + ring follower
- Inherits accent color from CSS variables

### Page Loader
- MK logo animation on page load
- 1.5 second fade-in effect
- Smooth transition to content

### Animations

| Feature | Trigger | Effect |
|---------|---------|--------|
| Glitch Text | Page Load | Text shadow flickering on name |
| Typewriter | Page Load | Cycling role titles |
| Scroll Indicator | Hero Section | Bouncing arrow animation |
| Fade-In Sections | Scroll into view | Sequential fade + slide up |
| Stat Counters | About section visible | Number counting animation |
| Card Hover | Mouse over cards | Scale + glow effect |
| Cert Card Flip | Click on card | 3D flip animation |
| Link Underline | Hover on nav | Expanding underline |
| Badge Pulse | Load | Radiating pulse animation |

### Scroll Behavior
- Smooth scrolling site-wide
- Active nav link highlighting based on scroll position
- Intersection Observer for entrance animations

## 📱 Responsive Design

### Breakpoints

| Device | Width | Adjustments |
|--------|-------|-------------|
| Mobile | 375px | Single column layouts, hamburger menu, smaller fonts |
| Tablet | 768px | 2-column grids, touch-friendly buttons |
| Desktop | 1440px | Full-featured layout, custom cursor, all animations |

**Mobile Menu**
- Hamburger icon appears on screens < 768px
- Smooth slide-down animation
- Auto-closes when a link is clicked

## 🔧 Technical Details

### Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### File Size
- **Single file**: ~60KB (minified HTML with embedded CSS & JS)
- **Load time**: < 1 second on modern connections
- **No external dependencies** (except Google Fonts)

### Performance Optimizations

1. **CSS-based Animations** - GPU-accelerated for smooth 60fps
2. **Intersection Observer** - Efficient scroll-triggered animations
3. **Canvas Rendering** - Optimized star particle background
4. **Event Delegation** - Minimal event listener overhead
5. **CSS Variables** - Easy theme customization without repainting
6. **Smooth Scroll** - Native HTML scroll-behavior

### Code Structure

```
styles/
├── Reset & Base (Global defaults)
├── Root Variables (Colors, spacing)
├── Scrollbar Styling
├── Loader Animation
├── Custom Cursor
├── Navbar
├── Hero Section
├── General Section Styles
├── About Section
├── Skills Section
├── Projects Section
├── Certifications Section
├── Digital Presence Section
├── Contact Section
└── Responsive Design (@media queries)

scripts/
├── Loader
├── Custom Cursor
├── Hero Canvas (Star Background)
├── Typewriter Effect
├── Mobile Menu
├── Nav Link Active States
├── Intersection Observer
├── Stat Counters
├── Certification Card Flip
└── Event Listeners
```

## 🎨 Customization Tips

### Adding Custom Fonts

```html
<!-- In <head> section -->
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;600;700&display=swap" rel="stylesheet">
```

Then update CSS:
```css
body {
    font-family: 'YourFont', sans-serif;
}
```

### Adding More Projects

Duplicate the `.project-card` div and update:
- Project image emoji/icon
- Title and description
- Tech stack pills
- Tags
- Links

### Adding More Certifications

Duplicate the `.cert-card` div and update:
- Icon
- Certification name
- Category tag
- Back-side description

### Dark Mode / Light Mode Toggle

Add a theme switcher button to the navbar and toggle between color schemes using CSS variables.

## 🚀 Deployment

### GitHub Pages
1. Create a new repository named `yourusername.github.io`
2. Push `index.html` to main branch
3. Visit `https://yourusername.github.io`

### Netlify
1. Drag and drop `index.html` onto Netlify
2. Get instant hosting with HTTPS

### Traditional Hosting
1. Upload `index.html` to your web server
2. Access via your domain

## 📊 Section Details

### Hero Section Stats
- Animated elements: 5 (name, subtitle, badges, buttons, scroll indicator)
- Canvas particles: 100 moving stars
- Animation duration: 2.5 seconds total

### Skills Section Stats
- Total skill cards: 16
- Skill categories: 4
- Hover effects: Scale + glow + color change

### Certifications Section Stats
- Total certifications: 13
- Card types: 2-sided flip cards
- Animation on flip: 600ms smooth rotation

### Projects Section Stats
- Featured projects: 2
- Layout: Alternating image-left, content-right
- Hover effects: Border glow + shadow expansion

## 🎓 Learning Resources

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Grid, Flexbox, Custom Properties, Animations
- **Vanilla JavaScript** - No frameworks, pure ES6+
- **Canvas API** - Star particle background
- **Intersection Observer API** - Scroll animations
- **CSS Backdrop Filters** - Glassmorphism effects

### Key Concepts Demonstrated

1. **CSS Grid** - Complex responsive layouts
2. **CSS Flexbox** - Alignment and spacing
3. **CSS Custom Properties** - Theme variables
4. **CSS Animations** - Keyframes and transitions
5. **CSS Transforms** - 3D flip effects
6. **JavaScript Event Listeners** - User interactions
7. **Intersection Observer** - Performance-optimized animations
8. **Canvas API** - Dynamic backgrounds
9. **Responsive Design** - Mobile-first, breakpoint-based

## 🐛 Troubleshooting

### Animations Not Working?
- Check browser compatibility (Need modern browser)
- Ensure JavaScript is enabled
- Check console for errors (F12)

### Custom Cursor Not Showing?
- Custom cursor only appears on desktop (>768px width)
- Check that JavaScript is running
- Try a different browser

### Fonts Not Loading?
- Check internet connection
- Verify Google Fonts link is active
- Fallback fonts should still display

### Responsive Layout Breaking?
- Check viewport meta tag is present
- Ensure viewport width media queries are loading
- Test with browser dev tools device emulation

## 📄 License

This portfolio website is custom-built and ready for personal use. All code is yours to modify and deploy.

## 💡 Future Enhancements

Potential additions:
- [ ] Dark/Light theme toggle
- [ ] Animated skill progress bars
- [ ] Blog or articles section
- [ ] Contact form
- [ ] Project filtering system
- [ ] Resume download button
- [ ] Testimonials section
- [ ] Analytics integration

## 📞 Support

For questions or issues:
1. Check the Customization Guide section
2. Review inline code comments
3. Inspect elements with browser DevTools
4. Test in multiple browsers

---

**Built with ❤️ for Meganandhitha K**

*Last Updated: March 2026*

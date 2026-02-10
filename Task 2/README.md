# Kalakgosi Maritz - Portfolio Website

A modern, dark-themed portfolio showcasing software engineering projects and skills.

## 🎨 Features

- **Dark Mode Design** - Easy on the eyes with cyan and purple accents
- **Smooth Animations** - Fade-ins, slide-ups, and interactive hover effects
- **Fully Responsive** - Looks great on desktop, tablet, and mobile
- **Interactive Elements** - Animated skill bars, typing effect, and more
- **Single Page Layout** - Smooth scrolling between sections
- **Custom Fonts** - Space Grotesk for headings, JetBrains Mono for code

## 📁 Files

```
portfolio/
├── portfolio.html          # Main HTML file
├── portfolio-styles.css    # All styling and animations
├── portfolio-script.js     # Interactive JavaScript features
└── README.md              # This file
```

## 🚀 Getting Started

1. Download all three files to the same folder
2. Open `portfolio.html` in your browser
3. That's it! No build process needed.

## ✏️ Customization Guide

### Update Your Info

**Personal Details** (in HTML):
- Name, school, location in the hero section
- Email and GitHub username throughout
- Project descriptions and technologies

**Projects**:
Replace the sample projects in the HTML with your actual projects. Each project card includes:
- Project number
- Title and description
- Technology tags
- GitHub link

**Skills**:
Update the skill bars and percentages to reflect your actual proficiency:
```html
<div class="skill-progress" style="width: 85%"></div>
```

**Learning Section**:
Add or remove technologies you're currently learning:
```html
<span class="learning-tag">Your Tech Here</span>
```

### Color Scheme

Want different colors? Edit these CSS variables at the top of `portfolio-styles.css`:

```css
:root {
    --bg-primary: #0a0a0a;         /* Main background */
    --accent-primary: #00d9ff;      /* Cyan accent */
    --accent-secondary: #7c3aed;    /* Purple accent */
    --text-primary: #e5e5e5;        /* Main text */
}
```

### Fonts

Currently using:
- **Space Grotesk** - Modern, geometric sans-serif
- **JetBrains Mono** - Code font for the hero section

To change fonts:
1. Visit [Google Fonts](https://fonts.google.com/)
2. Select your fonts
3. Replace the font link in the HTML `<head>`
4. Update `font-family` in CSS

## 🎯 Sections Breakdown

### Hero Section
- Eye-catching introduction with animated typing
- Code window showing your info as JavaScript object
- Two CTA buttons (customizable links)

### About Section
- Personal bio (3 paragraphs recommended)
- Animated stat cards
- Grid layout that stacks on mobile

### Projects Section
- Featured projects with hover effects
- Technology tags
- Links to GitHub repos
- "View more" link to your profile

### Skills Section
- Animated progress bars for main skills
- Separate section for technologies you're learning
- Organized by category (Frontend, Backend, etc.)

### Contact Section
- Email, GitHub, location cards with icons
- Contact form (currently console logs, needs backend)
- Responsive two-column layout

## 💡 Pro Tips

### Adding More Projects

Copy the project card HTML and paste it into the grid:
```html
<div class="project-card">
    <div class="project-number">05</div>
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-description">Description here...</p>
    <div class="project-tags">
        <span class="tag">Tech1</span>
        <span class="tag">Tech2</span>
    </div>
    <div class="project-links">
        <a href="your-link" class="project-link">View Code →</a>
    </div>
</div>
```

### Making the Form Work

The contact form currently logs to console. To make it functional:

1. **Use a service like Formspree**:
   - Sign up at formspree.io
   - Add their endpoint to your form action
   - Remove the preventDefault() in the JS

2. **Or build your own backend**:
   - Create an API endpoint (Node.js, Python, etc.)
   - Update the form submission handler in `portfolio-script.js`
   - Add proper validation and error handling

### SEO Improvements

1. Add meta description:
```html
<meta name="description" content="Software Engineering student passionate about web development">
```

2. Add Open Graph tags for social sharing
3. Create a favicon
4. Use semantic HTML (already done!)

## 🎨 Animation Details

The portfolio includes several smooth animations:

- **Fade-in**: Elements appear gradually
- **Slide-up**: Content slides in from bottom
- **Typing effect**: Hero subtitle types out
- **Skill bars**: Progress bars animate on scroll
- **Stat counters**: Numbers count up when visible
- **Parallax**: Hero elements move at different speeds
- **Hover effects**: Cards lift and glow on hover

All animations are smooth and respect user preferences for reduced motion.

## 📱 Responsive Breakpoints

- **Desktop**: > 968px (full layout)
- **Tablet**: 768px - 968px (adjusted grid)
- **Mobile**: < 768px (stacked layout)
- **Small Mobile**: < 480px (optimized for phones)

## 🐛 Troubleshooting

**Fonts not loading?**
- Check your internet connection (fonts load from Google)
- Or download fonts locally and update paths

**Animations not working?**
- Make sure JavaScript is enabled
- Check browser console for errors

**Layout looks broken?**
- Clear browser cache
- Make sure all three files are in the same folder

## 🔮 Future Enhancements

Ideas to take it further:

- Add a blog section
- Include a resume download button
- Integrate with GitHub API to show real projects
- Add dark/light mode toggle
- Include testimonials or recommendations
- Add a loading animation
- Create a custom 404 page

## 📄 License

Free to use and modify for your own portfolio!

---

**Built for Kalakgosi Maritz**  
Software Engineering Student @ Wits University  
Johannesburg, South Africa

Questions? Reach out: maritzkalakgosi@gmail.com

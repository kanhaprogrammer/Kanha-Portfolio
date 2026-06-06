# Kanha Sharma | Web Developer & Founder of WebInstant

![Portfolio Preview](kanha-programmer.jpeg)

A modern, responsive portfolio website showcasing Kanha Sharma's work as a web developer and founder of WebInstant. Built with vanilla HTML, CSS, and JavaScript — featuring a futuristic cyberpunk aesthetic with animated gradients, dynamic typing effects, and smooth interactions.

## 🌟 Live Demo

[View Portfolio](https://kanhaprogrammer.github.io/portfolio)

## ✨ Features

- **Dynamic Typing Animation** - Rotating role descriptions with typewriter effect
- **Fully Responsive** - Mobile-first design that looks great on all devices
- **Smooth Scroll Reveal** - Elements animate into view as you scroll
- **Interactive Background** - Canvas-based animated particle/glow background
- **Contact Form** - Integrated with Formspree for message handling
- **Client Reviews Section** - Social proof with star ratings
- **Project Showcase** - Live links to deployed projects
- **Social Media Integration** - Connect via WhatsApp, LinkedIn, GitHub, Instagram, and more

## 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| Icons | Font Awesome 6 |
| Fonts | Google Fonts (Inter, Space Grotesk) |
| Forms | Formspree API |
| Deployment | GitHub Pages |

## 📁 Project Structure

```
portfolio/
├── index.html              # Main portfolio file
├── kanha-programmer.jpeg   # Profile image
├── webinstant-website.png  # WebInstant project thumbnail
├── Kanha-Expense-Tracker.png # Expense Tracker thumbnail
├── Daily-Tracker.png       # Daily Tracker thumbnail
└── README.md               # Documentation
```

## 🚀 Sections

1. **Home/Hero** - Introduction, stats, CTA buttons, and animated avatar
2. **About** - Bio and key strengths (clean code, mobile-first, fast, SEO-friendly)
3. **Skills** - Technology stack with hover animations
4. **Services** - Offerings: Web Development, Responsive Design, SEO, Hosting
5. **Projects** - Live portfolio with links to deployed work
6. **Reviews** - Client testimonials
7. **Contact** - Email, WhatsApp, location, and functional contact form

## 🎨 Color Palette

| Variable | Color | Usage |
|----------|-------|-------|
| `--bg` | `#010101` | Primary background |
| `--c` | `#00f0ff` | Cyan accent |
| `--cp` | `#8b5cf6` | Purple accent |
| `--cg` | `#10b981` | Green accent |
| `--muted` | `#6b7280` | Secondary text |

## 📱 Responsive Breakpoints

- **Desktop** - Full layout with avatar visible
- **Tablet (≤900px)** - Stacked layout, avatar hidden
- **Mobile (≤768px)** - Hamburger menu activated
- **Small Mobile (≤480px)** - Compact spacing and typography

## 🔧 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kanhaprogrammer/portfolio.git
   ```

2. **Navigate to project directory**
   ```bash
   cd portfolio
   ```

3. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use Live Server extension in VS Code

## 📝 Customization

### Update Personal Info
Edit the following sections in `index.html`:
- Name, title, bio → Hero section
- Email and WhatsApp → Contact section
- Social media links → Footer section

### Add/Remove Projects
Modify the `.projects-grid` section in HTML:
```html
<article class="proj reveal">
    <div class="proj-thumb">
        <img src="your-image.png" alt="Project name">
    </div>
    <div class="proj-body">
        <h3>Project Title</h3>
        <p>Description</p>
        <div class="tags">...</div>
        <a href="https://your-link.com" class="proj-link">View Live →</a>
    </div>
</article>
```

### Modify Typing Lines
Update the `lines` array in the script:
```javascript
const lines = [
    'Your New Title 1',
    'Your New Title 2',
    // Add more...
];
```

## 📧 Contact Form

The form uses **Formspree** (free tier). To use your own endpoint:

1. Sign up at [Formspree](https://formspree.io)
2. Create a new form
3. Replace `action="https://formspree.io/f/maqabkgn"` with your endpoint

## 🌐 Social Links

Current connections:
- WhatsApp: `+91 98710 72210`
- LinkedIn: `@kanha-programmer`
- GitHub: `@kanhaprogrammer`
- Instagram: `@kanhaprogrammer`
- X/Twitter: `@KanhaSProgramer`
- Facebook: `Kanha Sharma`
- YouTube: `@KanhaProgrammer`
- Linktree: `@kanhaprogrammer`

## 📄 License

© 2026 Kanha Sharma · WebInstant. All rights reserved.

## 👨‍💻 Author

**Kanha Sharma**
- Web Developer from Ghaziabad, India
- Founder of [WebInstant](https://webinstant-works.github.io/WebInstant/index.html)
- Email: [kanhaprogrammer.exe@gmail.com](mailto:kanhaprogrammer.exe@gmail.com)

---

⭐ Star this repository if you found it useful!

# Personal Website - AI Product Manager
## Professional Portfolio for CS + Business + Research

### 📋 Overview

A modern, tech-forward personal website designed specifically for an aspiring AI Product Manager. Balances technical credibility with business acumen, featuring a clean design system optimized for both technical recruiters and business-minded hiring managers.

**Live Preview:** [Your domain here]

---

## 🎨 Design Philosophy

**Style:** Tech-Minimalist (Bento Box + Minimalist Hybrid)
- **Minimalism:** Intentional whitespace, no unnecessary decoration
- **Tech-Forward:** Modern typography, subtle animations, data visualization
- **Accessibility:** High contrast, keyboard navigation, mobile-optimized
- **Product-Thinking:** Every element communicates value

**Color Palette:**
- Primary: Deep Navy (`#1A1F36`) - Professional, stable, intelligent
- Accent: Electric Blue (`#0066FF`) - Innovation, tech-forward
- Supporting: Warm Gray (`#6B7280`) - Human, readable
- Success: Green (`#10B981`) - Achievements, badges
- Innovation: Purple (`#8B5CF6`) - AI/Data sections
- Strategy: Amber (`#F59E0B`) - Product/Business sections

---

## 📁 File Structure

```
personal_website/
├── index.html           # Main HTML file (update with your info)
├── styles.css          # CSS styling (Tech-Minimalist design system)
├── script.js           # JavaScript for interactions
├── content.md          # All website copy & content
├── DESIGN_GUIDE.md     # Design system specifications
├── README.md           # This file
└── assets/             # (Optional) Images, favicons, etc.
    ├── favicon.ico
    ├── og-image.png
    └── hero-bg.svg
```

---

## 🚀 Quick Start

### 1. **Clone/Download the Repository**
```bash
git clone https://github.com/your-username/personal_website.git
cd personal_website
```

### 2. **Customize Your Information**

Edit `index.html` and replace the following placeholders:

```html
<!-- In <meta> tags -->
<meta name="author" content="YOUR NAME">
<meta property="og:title" content="YOUR TITLE | AI Product Manager">

<!-- In contact section -->
<a href="mailto:your-email@oregonstate.edu">
<a href="https://linkedin.com/in/your-profile" target="_blank">
<a href="https://github.com/your-profile" target="_blank">
<a href="https://calendly.com/your-link" target="_blank">
```

### 3. **Update Content**

Review `content.md` and customize:
- Hero headlines
- Bio details
- Skills (add/remove as needed)
- Experience dates and metrics
- Awards and certifications
- Contact information

### 4. **Test Locally**

Open `index.html` in your browser:
```bash
open index.html  # macOS
# or drag the file into your browser
```

### 5. **Deploy**

Choose one of these free hosting options:

#### **Option A: GitHub Pages** (Recommended)
1. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial personal website"
   git push origin main
   ```
2. Go to Settings → Pages → Select `main` branch → Save
3. Your site will be live at: `https://username.github.io/personal_website`

#### **Option B: Vercel** (Easy & Fast)
1. Visit [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Vercel auto-deploys on every push

#### **Option C: Netlify** (User-Friendly)
1. Drag your project folder to [netlify.com](https://netlify.com)
2. Get a live URL instantly
3. Connect to GitHub for auto-deployment

---

## 🎯 Customization Guide

### **Update Hero Section**
Edit the headline and sub-headline in `index.html`:
```html
<h1 class="hero-title">
    Where <span class="accent">Code</span> Meets <span class="accent">Strategy</span>
</h1>
<p class="hero-subtitle">Your custom subtitle here</p>
```

### **Modify Color Scheme**
Edit CSS variables in `styles.css`:
```css
:root {
    --color-accent-blue: #0066FF;    /* Change primary accent */
    --color-navy: #1A1F36;            /* Change primary text color */
    --color-success: #10B981;         /* Change badge/award color */
}
```

### **Add New Skills**
Add skill tags to the appropriate category:
```html
<li><span class="skill-tag">Your Skill</span></li>
```

### **Add New Experience**
Duplicate the `.experience-card` section:
```html
<div class="experience-card">
    <div class="exp-header">
        <div class="exp-title">
            <h3>Your Position</h3>
            <p class="exp-company">Company Name</p>
        </div>
        <div class="exp-date">Duration</div>
    </div>
    <!-- Add content -->
</div>
```

### **Add Projects Section** (Optional)
Create a new section after Experience:
```html
<section id="projects" class="section projects-section">
    <div class="container">
        <h2 class="section-title">Featured Projects</h2>
        <div class="projects-grid">
            <!-- Add project cards here -->
        </div>
    </div>
</section>
```

Then add CSS for `.projects-grid` similar to `.skills-grid`.

---

## ✨ Features

- ✅ **Responsive Design** – Mobile-first, tested on all devices
- ✅ **Dark Mode Ready** – Automatically respects system preferences
- ✅ **Smooth Animations** – Fade-in effects, hover states, scroll interactions
- ✅ **SEO Optimized** – Meta tags, semantic HTML, Open Graph support
- ✅ **Accessibility** – WCAG compliant, keyboard navigation, high contrast
- ✅ **Performance** – Optimized CSS/JS, minimal dependencies, fast load times
- ✅ **Contact Integration** – Links to email, LinkedIn, GitHub, Calendly
- ✅ **Analytics Ready** – Built-in hooks for Google Analytics

---

## 📱 Responsive Breakpoints

- **Mobile:** 320px–599px (Single column)
- **Tablet:** 600px–1023px (2-column layouts)
- **Desktop:** 1024px–1439px (Full Bento Box)
- **Wide Desktop:** 1440px+ (Max-width container)

---

## 🔍 SEO & Meta Tags

The site includes meta tags for:
- **Open Graph** (Social sharing)
- **Twitter Card** (Tweet sharing)
- **Description** (Search results snippet)
- **Keywords** (Search engines)

Update these in `<head>`:
```html
<meta name="description" content="Your description here">
<meta property="og:title" content="Your Title">
```

---

## 🛠️ Browser Support

- ✅ Chrome/Edge (Latest 2 versions)
- ✅ Firefox (Latest 2 versions)
- ✅ Safari (Latest 2 versions)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📊 Analytics Setup (Optional)

### Google Analytics
1. Create a Google Analytics account
2. Get your Measurement ID
3. Add to `script.js`:
   ```javascript
   // Replace MEASUREMENT_ID
   gtag('config', 'G-XXXXXXXXXX');
   ```

### Google Search Console
1. Add your site at [search.google.com/search-console](https://search.google.com/search-console)
2. Verify ownership
3. Submit your sitemap

---

## 🎓 Career Positioning Tips

### Keywords for LinkedIn/Portfolio
- AI Product Manager
- Hardware-Software Integration
- Automation & Data Analysis
- CS + Business Strategy
- Research-Driven Product Design

### What Recruiters Look For
1. **Technical Credibility** – Specific skills, projects, research
2. **Product Thinking** – Business impact metrics (e.g., "35% time saved")
3. **Communication** – Clear, jargon-free copy accessible to non-technical folks
4. **Growth Mindset** – Certifications, learning, ambition
5. **Team Collaboration** – Cross-functional experience

### Optimization Suggestions
- Add GitHub link to showcase projects
- Create a blog section (great for AI/PM insights)
- Include testimonials from mentors/research advisors
- Add metrics to every achievement (quantify impact)
- Keep portfolio updated with new projects/awards

---

## 🚢 Deployment Checklist

Before going live:

- [ ] All placeholder text replaced with your information
- [ ] Contact links updated (email, LinkedIn, GitHub, Calendly)
- [ ] Email address verified and working
- [ ] LinkedIn and GitHub profiles are public and complete
- [ ] No broken links (test all navigation)
- [ ] Mobile view tested on phone/tablet
- [ ] Dark mode tested (if system supports it)
- [ ] Google Analytics set up (if using)
- [ ] Domain purchased (optional, GitHub Pages is free)
- [ ] Open Graph images added (for social sharing)
- [ ] README updated with custom info

---

## 📚 Resources

### Learning & Development
- [Google Analytics Setup](https://support.google.com/analytics)
- [Web Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/WCAG21/quickref/)
- [SEO Starter Guide](https://developers.google.com/search/docs)
- [MDN Web Docs](https://developer.mozilla.org/) – HTML/CSS/JavaScript reference

### Design Tools
- [Figma](https://figma.com) – Design mockups
- [Coolors](https://coolors.co) – Color palette generator
- [Google Fonts](https://fonts.google.com) – Typography

### Hosting & Deployment
- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [Cloudflare Pages](https://pages.cloudflare.com/)

### Additional Features
- [Calendly](https://calendly.com) – Scheduling
- [Mailchimp](https://mailchimp.com) – Newsletter
- [Disqus](https://disqus.com) – Comments (for blog)

---

## 🐛 Troubleshooting

### Site not showing up on GitHub Pages?
- Ensure branch is set to `main` in Settings → Pages
- Check that `index.html` is in the root directory
- Wait 5-10 minutes for initial deployment

### Styles not loading?
- Clear browser cache (Cmd+Shift+R on macOS)
- Check that `styles.css` is in the same directory as `index.html`
- Verify file paths are correct (no typos)

### Smooth scrolling not working?
- Ensure JavaScript is enabled in browser
- Check browser compatibility (older browsers may not support)
- Verify `script.js` is linked in `index.html`

### Links not working?
- Check that contact email is correct: `mailto:your-email@domain.com`
- Verify social profile URLs are public
- Test in incognito mode (rules out caching issues)

---

## 💡 Next Steps

### Short-term (Week 1-2)
1. Customize all personal information
2. Deploy to GitHub Pages or Vercel
3. Share link with mentors for feedback
4. Add to resume/LinkedIn

### Medium-term (Month 1-2)
1. Add GitHub projects showcase
2. Start a blog section (AI/PM insights)
3. Collect LinkedIn testimonials
4. Optimize based on recruiter feedback

### Long-term (Ongoing)
1. Update with new projects and achievements
2. Add case studies or detailed project breakdowns
3. Expand to include speaking/event appearances
4. Maintain as you progress through your CS program

---

## 📄 License

This website template is open-source. Feel free to use, modify, and share!

---

## 🤝 Contributing

Suggestions for improvement? Found a bug?
1. Open an issue on GitHub
2. Submit a pull request with improvements
3. Share feedback with the creator

---

## ✉️ Questions?

For questions about this template or personalization help:
- Review the `DESIGN_GUIDE.md` for detailed specifications
- Check `content.md` for all copy templates
- Refer to inline HTML comments for guidance

---

**Built with ❤️ for aspiring AI Product Managers**

---

*Last Updated: March 2026*
*Template Version: 1.0*


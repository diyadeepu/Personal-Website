# Quick Reference: Customization Guide

## 🚀 30-Minute Setup

### Step 1: Update Personal Information (5 min)
1. Open `index.html`
2. Use Find & Replace (Cmd+F):
   - Replace `"Your Name"` with your actual name
   - Replace `your-email@oregonstate.edu` with your email
   - Replace `linkedin.com/in/your-profile` with your LinkedIn URL
   - Replace `github.com/your-profile` with your GitHub URL
   - Replace `calendly.com/your-link` with your Calendly link

### Step 2: Update Content (10 min)
1. Review `content.md` for all copy templates
2. Update dates in Experience section (look for "Present")
3. Customize MIME Lab achievements (update the 35% metric if needed)
4. Add any additional certifications in Awards section

### Step 3: Customize Colors (5 min)
Edit `styles.css`, find `:root` section:
```css
--color-accent-blue: #0066FF;    /* Change to your brand color */
```

### Step 4: Deploy (10 min)
Choose one:
- **GitHub Pages:** Push to GitHub, enable Pages in Settings
- **Vercel:** Connect GitHub repo, auto-deploys
- **Netlify:** Drag folder to site, instant deploy

---

## 📝 Content Sections: What to Update

### Hero Section
```html
<h1 class="hero-title">
    Where <span class="accent">Code</span> Meets <span class="accent">Strategy</span>
</h1>
```
✏️ Customize the highlighted words based on your focus

### About Section (Quick Stats)
Each stat card has:
- Icon (emoji)
- Label (e.g., "Education")
- Value (e.g., "CS Major + Business Minor")
- Detail (e.g., "OSU Honors College")

### Skills Section
Three categories (customizable):
- **Development:** Python, Java, etc.
- **AI & Data:** TensorFlow, SQL, etc.
- **Product & Business:** Agile, Market Analysis, etc.

Add/remove skills by editing skill-tag items.

### Experience Section
- **Position & Company**
- **Duration** (or "Present")
- **Impact points** (use metrics!)
- **Skills used**
- **Key insight quote**

### Awards Section
Three cards for:
1. Honors College recognition
2. Scholarships/academic awards
3. Future certifications

### Contact Section
Update all four contact methods:
- Email
- LinkedIn
- GitHub
- Calendly

---

## 🎨 Color Customization Examples

### Tech-Focused Brand
```css
--color-accent-blue: #FF6B6B;    /* Vibrant red */
--color-purple: #6366F1;          /* Deep purple */
--color-amber: #EC4899;           /* Hot pink */
```

### Minimalist Professional
```css
--color-accent-blue: #334155;     /* Slate blue */
--color-navy: #0F172A;            /* Deep charcoal */
--color-gray: #64748B;            /* Soft gray */
```

### Warm & Approachable
```css
--color-accent-blue: #D97706;     /* Warm amber */
--color-purple: #DC2626;          /* Red accent */
--color-navy: #78350F;            /* Warm brown */
```

---

## 📊 Adding Impact Metrics

**Before:**
"Designed and implemented Python scripts for manufacturing data"

**After:**
"Designed and implemented Python scripts to streamline manufacturing data processing, reducing analysis time by **35%**"

✨ Recruiters love numbers!

---

## 🔗 Important Links to Replace

```
Email:    mailto:your-email@oregonstate.edu
LinkedIn: https://linkedin.com/in/your-profile
GitHub:   https://github.com/your-profile
Calendly: https://calendly.com/your-link
```

---

## ✅ Pre-Launch Checklist

- [ ] All placeholder text replaced
- [ ] Contact links tested (try clicking them)
- [ ] Mobile view looks good (test on phone)
- [ ] Dark mode works (if browser supports)
- [ ] No broken navigation links
- [ ] GitHub/LinkedIn profiles are public
- [ ] Email address is correct
- [ ] Hero section headline is compelling
- [ ] Experience metrics are included
- [ ] All file paths are correct

---

## 🚢 Deployment Links

After deploying, these will be your live URLs:

**GitHub Pages:**
```
https://your-github-username.github.io/personal_website
```

**Vercel:**
```
https://personal-website-xxxxxxx.vercel.app
(You can set custom domain)
```

**Netlify:**
```
https://your-domain.netlify.app
(You can set custom domain)
```

---

## 💡 Pro Tips

1. **Make sure email works** – Test sending yourself an email from the site
2. **Use specific metrics** – "35% faster" > "faster"
3. **Update regularly** – Add new projects, skills, awards as you progress
4. **Get feedback** – Share with professors, mentors, peers before going live
5. **Add to LinkedIn** – Link your portfolio in LinkedIn profile
6. **Keep it fresh** – Update every semester with new achievements

---

## 🎯 For Recruiters: What They See

1. **Hero Section** – Your headline (5 seconds)
2. **About Section** – Who you are (10 seconds)
3. **Skills** – Technical credibility (5 seconds)
4. **Experience** – Impact & metrics (20 seconds)
5. **Awards** – Achievements (5 seconds)
6. **Contact** – How to reach you (Immediate action)

**Total attention span: ~45 seconds. Make it count!**

---

## 🚀 Going Live Checklist

1. ✅ Customize content
2. ✅ Test locally (open in browser)
3. ✅ Deploy to hosting platform
4. ✅ Test live site on mobile
5. ✅ Share with mentors/peers
6. ✅ Add to resume
7. ✅ Update LinkedIn profile
8. ✅ Share on social media
9. ✅ Monitor for broken links
10. ✅ Update regularly!

---

## 📞 Quick Support

**Site looks broken?**
- Clear cache: Cmd+Shift+R
- Reload page: Cmd+R
- Check console for errors: Cmd+Option+J

**Something isn't working?**
- Check file names (case-sensitive on Linux/Mac)
- Verify all paths in HTML are correct
- Make sure styles.css and script.js are in same folder as index.html

**Need to make changes after deploying?**
- Edit files → Git push → Auto-deploys in 30 seconds
- No need to manually refresh (unless using GitHub Pages)

---

*Happy building! 🚀*


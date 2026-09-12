# Design System & Branding Guide
## Personal Website for AI Product Manager

---

## DESIGN APPROACH: "Tech-Minimalist"

A strategic blend of:
- **Minimalism:** Clean, intentional whitespace; no unnecessary elements
- **Tech-Forward:** Modern typography, subtle animations, data visualization
- **Accessibility:** Clear hierarchy, high contrast, readable on all devices
- **Product-Thinking:** Every design choice serves a purpose and communicates value

This approach signals to viewers (whether technical recruiters or business-minded hiring managers) that you think like both an engineer and a strategist.

---

## COLOR PALETTE

### Primary Palette
- **Deep Navy/Charcoal:** `#1A1F36` – Primary background, headers, body text
  - Conveys professionalism, stability, intelligence
  - Easy on eyes for extended reading

- **Bright Accent (Electric Blue):** `#0066FF` or `#00D9FF`
  - Used for CTAs, links, highlights
  - Signals innovation and tech-forward thinking
  - High contrast for accessibility

- **Soft White/Off-White:** `#F8F9FA` or `#FAFBFC` – Secondary background
  - Card backgrounds, sections
  - Prevents pure white fatigue while maintaining cleanliness

- **Warm Gray (Supporting):** `#6B7280` – Secondary text, captions, subtle elements
  - Better for readability than pure black/gray
  - Humanizes the minimalist aesthetic

### Accent Colors (Use Sparingly)
- **Success Green:** `#10B981` – For badges, achievements
- **Subtle Purple:** `#8B5CF6` – For "AI/Data" section headers (signals innovation)
- **Warm Amber:** `#F59E0B` – For "Product/Business" section (signals strategy)

### Dark Mode Ready
Since you're targeting tech-savvy audiences, design with dark mode support:
- Light Mode: Navy text on soft white backgrounds
- Dark Mode: Soft white text on deep navy backgrounds
- Accent colors remain consistent

---

## TYPOGRAPHY

### Font Stack (Modern & Professional)
- **Headings:** `'Inter', 'Helvetica Neue', sans-serif`
  - Modern, geometric, excellent readability
  - Communicates contemporary thinking
  - Weights: 700 (bold), 600 (semi-bold)

- **Body Text:** `'Inter', system fonts, sans-serif`
  - Same family as headings for cohesion
  - Weight: 400 (regular), 500 (medium for emphasis)
  - Line height: 1.6 for comfortable reading

- **Code/Technical Elements:** `'Jetbrains Mono'` or `'Monaco'` monospace
  - Shows coding credibility
  - Use for GitHub links, technical details

### Sizing Hierarchy
- **Hero Headline:** 48–56px (desktop), 36–42px (mobile)
- **Section Headers:** 32–36px
- **Subheaders:** 24–28px
- **Body Text:** 16–18px
- **Captions/Meta:** 12–14px

---

## LAYOUT STRUCTURE: Recommended Approach

### Option A: "Bento Box" (Recommended for You)
**Why it works:** Mirrors product design thinking, visually interesting, great for showcasing diverse skills

**Structure:**
```
[Hero Section - Full Width]
    ↓
[About / Bio - 2/3 width left, Quick Stats - 1/3 width right]
    ↓
[Skills Grid - 3 columns, each skill category in a "box"]
    ↓
[Experience - Full Width Card]
    ↓
[Awards/Certs - 2-3 columns of cards]
    ↓
[CTA + Footer]
```

**Visual Feel:** Each section is a self-contained "tile" with subtle shadows and rounded corners (8px border radius). Creates a modular, organized impression.

### Option B: "Minimalist Linear"
**Why:** Ultra-clean, maximum focus on copy, very professional

**Structure:**
```
[Hero - Full Width, centered]
    ↓
[Sections stacked vertically, each full-width with alternating backgrounds]
    ↓
[Right-aligned images/graphics as needed]
```

**Visual Feel:** Zen-like, high impact, emphasis on substance over decoration.

### Option C: "Tech-Futurist" (More Complex)
**Why:** Cutting-edge, appeals to AI-focused audiences, requires more effort

**Features:** 
- Grid-based design with slight angles (CSS `skew`)
- Animated data visualizations
- Glassmorphism cards (frosted glass effect)
- Scrollytelling effects

**Note:** Higher complexity—use if you have development bandwidth.

---

## RECOMMENDED: Bento Box + Minimalist Hybrid

**Here's what I recommend for you:**

**Hero Section:**
- Full-width, gradient background (deep navy → slightly lighter navy)
- Centered text with electric blue accent on key words
- Subtle geometric shape (SVG) in background corner (signals design thinking)

**Content Sections:**
- Alternating left/right layouts for visual rhythm
- Cards with 8px rounded corners, subtle shadows (`0 4px 12px rgba(0,0,0,0.08)`)
- Section headers in semi-bold Inter, 32px
- Skill boxes in 3-column grid, each with icon + label

**Interactive Elements:**
- Smooth hover effects on links (color change + underline animation)
- CTA button changes color and slight scale on hover
- Navbar: sticky position, minimal (logo + contact link)

**Whitespace:**
- Generous margins between sections (64px–80px desktop, 40px mobile)
- Line height 1.6–1.8 for body text
- Breathing room around each element

---

## KEY DESIGN PRINCIPLES FOR AI PM POSITIONING

1. **Intentionality:** Every element has a purpose. No decoration without function.
2. **Data-Driven Aesthetics:** Use subtle metrics/stats to show analytical mindset (e.g., "35% time saved" badge on MIME project)
3. **Accessibility First:** High contrast, keyboard navigation, mobile-first responsive design
4. **Scalability:** Design is modular—easy to add projects, skills, awards as you progress
5. **Technical Credibility:** Hint at technical depth without overwhelming (e.g., GitHub link, code snippets optional)
6. **Business Acumen:** Modern, polished design signals product sophistication

---

## RESPONSIVE DESIGN BREAKPOINTS

- **Mobile (320px–599px):** Single column, larger touch targets
- **Tablet (600px–1023px):** 2-column layouts
- **Desktop (1024px+):** Full Bento Box with 3-column grids
- **Wide Desktop (1440px+):** Max-width container to prevent text lines from becoming too long

---

## VISUAL HIERARCHY EXAMPLE

**Hero Section:**
```
[Electric Blue Accent] HEADLINE TEXT (Primary)
Sub-headline in warm gray (Secondary)
Small CTA button with electric blue
```

**Skill Cards:**
```
[Icon/Badge in Electric Blue]
Skill Category (Semi-bold, Navy)
5-7 items in regular text (Navy)
```

**Experience Card:**
```
[Company/Role Header in Electric Blue or Bold Navy]
Duration in warm gray
Description in body text
[Tags/Skills at bottom in electric blue]
```

---

## IMPLEMENTATION TIPS

1. **Use a CSS framework for speed:** Tailwind CSS (recommended) or Bootstrap
2. **Animations:** Subtle fade-ins, slide-ups on scroll (use Intersection Observer API)
3. **Dark mode toggle:** Add a sun/moon icon in header for user preference
4. **Performance:** Optimize images, lazy load sections, minimal dependencies
5. **SEO:** Semantic HTML, meta tags, open graph for sharing
6. **Analytics:** Light tracking (Google Analytics) to understand visitor behavior

---

## MOCKUP DESCRIPTION

If you were to create a visual mockup:

```
┌─────────────────────────────────────────────┐
│         PERSONAL WEBSITE MOCKUP             │
├─────────────────────────────────────────────┤
│                                             │
│  [HERO]                                     │
│  Where Code Meets Strategy                  │
│  [Blue accent on key words]                 │
│  [Subtle geometric background]              │
│                                             │
├─────────────────────────────────────────────┤
│  [ABOUT] (2/3)    │  [QUICK STATS] (1/3)   │
│  Bio text...      │  • CS Major            │
│                   │  • OSU Honors          │
│                   │  • Research Assistant  │
│                   │                        │
├─────────────────────────────────────────────┤
│  [SKILLS GRID - 3 COLUMNS]                  │
│  [Dev Box] [AI/Data Box] [PM Box]          │
│                                             │
├─────────────────────────────────────────────┤
│  [EXPERIENCE CARD - Full Width]             │
│  MIME Research Assistant                    │
│  Description with impact metrics...         │
│                                             │
├─────────────────────────────────────────────┤
│  [AWARDS - 3 Columns]                       │
│  [Honors Box] [Scholar Box] [Cert Box]     │
│                                             │
├─────────────────────────────────────────────┤
│  [CTA + FOOTER]                             │
│  Let's talk... [Email] [LinkedIn] [GitHub] │
│                                             │
└─────────────────────────────────────────────┘
```

---

## NEXT STEPS

1. Choose your tech stack: HTML/CSS (vanilla) or React + Tailwind
2. Set up a GitHub repo for version control
3. Deploy to Vercel, Netlify, or GitHub Pages (free options)
4. Iterate based on feedback from mentors/peers
5. Consider adding a blog section later (great for AI/PM insights)


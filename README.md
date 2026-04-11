# 🌍 CLIMA – SDG 13 Climate Action Website

A student-built, multi-page website exploring **UN Sustainable Development Goal 13 (Climate Action)** with a focus on Nepal. Built as a group project at the **University of Westminster, 2026**.

---

## 📋 Project Overview

CLIMA is a static HTML/CSS/JS website that educates visitors about climate change, empowers them to take action, and demonstrates the impact of everyday choices. The site is targeted at students and young people in Nepal and globally.

---

## 🗂️ Site Structure

```
clima/
├── splash.html              # Animated splash / loading screen
├── home.html                # Home page – mission, cards, topic gallery
├── gallery.html             # Climate photo gallery with modal viewer
├── ais.html                 # Action Impact Simulator (interactive)
├── feedback.html            # User feedback form
├── team.html                # Meet the team
├── profile.html             # Build your climate action profile
├── sitemap.html             # Interactive SVG sitemap
│
├── content_ST1.html         # Student 1 – Renewable Energy in Nepal
├── content_ST2.html         # Student 2 – Sustainable Transport in Nepal
├── content_ST3.html         # Student 3 – Green Consumption in Nepal
├── content_ST4.html         # Student 4 – Nepal's Climate Policy
│
├── pageEditor_ST1.html      # Page editor log – Student 1
├── pageEditor_ST2.html      # Page editor log – Student 2
├── pageEditor_ST3.html      # Page editor log – Student 3
├── pageEditor_ST4.html      # Page editor log – Student 4
│
├── validation_ST1.html      # W3C validation evidence – Student 1
├── validation_ST2.html      # W3C validation evidence – Student 2
├── validation_ST3.html      # W3C validation evidence – Student 3
│
├── style.css                # Shared global stylesheet
└── images/                  # Local validation screenshots
```

---

## ✨ Key Features

- **Splash Screen** – Animated intro with 4-second auto-redirect and skip button
- **Interactive Gallery** – Hover effects, modal pop-ups, colour & font customisation
- **Action Impact Simulator (AIS)** – Select climate actions, see a live impact score and dynamic background
- **Climate Profile Builder** – Step-by-step prompt-driven personal profile with progress tracking
- **Interactive Sitemap** – Clickable SVG diagram of the full site hierarchy
- **Responsive Design** – Mobile-first with hamburger navigation on small screens
- **Accessibility** – ARIA labels, keyboard navigation, semantic HTML throughout

---

## 🛠️ Technologies Used

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantics |
| CSS3 | Global stylesheet (`style.css`) + embedded page-specific styles |
| Vanilla JavaScript | Interactivity (AIS, gallery modal, profile builder, nav toggle) |
| Google Fonts | Bebas Neue (display), DM Sans (body), Space Mono (mono) |
| Unsplash / external CDNs | Hero and gallery imagery |
| W3C Validator | HTML validation for all pages |

---

## 👥 Team

| Student | ID | Pages |
|---|---|---|
| Pritisha Dawadee | W2148849 | Template, Home, Gallery, Content ST1 |
| Ajit Pandey | W2148848 | Splash, Action Impact Simulator, Content ST2 |
| Najni Khatoon | W2152992 | Feedback, Team, Content ST3 |
| Subina Upreti | W2148855 | Profile, Sitemap, Content ST4 |

---

## 🚀 Getting Started

No build tools or dependencies required. This is a pure static site.

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/clima.git
   cd clima
   ```

2. **Open in a browser**
   Simply open `splash.html` or `home.html` in any modern browser.
   ```bash
   # Or use a local dev server (recommended to avoid CORS issues with images)
   npx serve .
   ```

3. **Start exploring**
   The entry point is `splash.html` → auto-redirects to `home.html` after 4 seconds.

---

## ✅ Validation

All HTML pages were validated using the [W3C Markup Validation Service](https://validator.w3.org/). See the individual validation pages for screenshots and reflection notes:

- [validation_ST1.html](validation_ST1.html) – Home, Gallery, Content ST1
- [validation_ST2.html](validation_ST2.html) – Splash, AIS, Content ST2
- [validation_ST3.html](validation_ST3.html) – Feedback, Team, Content ST3

---

## 🎨 Design System

The shared `style.css` defines a consistent design language across all pages:

- **Primary colour:** `#1a6b3c` (forest green)
- **Accent colour:** `#f4a020` (warm amber)
- **Display font:** Bebas Neue
- **Body font:** DM Sans
- **Border radius:** 8px / 16px
- **Responsive breakpoints:** 768px (mobile nav), 900px (grid reflow)

Page-specific styles are embedded within each HTML file's `<style>` block and do not affect other pages.

---

## 📄 License

This project was created for educational purposes as part of a university coursework assignment. All images are sourced from [Unsplash](https://unsplash.com) (free to use) or credited within the page where applicable.

---

*© 2026 CLIMA – SDG 13 Climate Action | University of Westminster*

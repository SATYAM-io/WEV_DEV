# Cursor Landing Page Clone 🖱️

A pixel-perfect recreation of the [Cursor.com](https://cursor.com) landing page, built entirely with raw **HTML & CSS**. This project focuses on structural accuracy, semantic markup, and modern CSS layout techniques (Flexbox & Grid) without relying on any frameworks like Tailwind or Bootstrap.

![PRIVEW](assets/screenshots/screenshot.png)

---

## 📝 Project Details

**Goal:** Recreate the visual hierarchy, typography, and layout of the Cursor developer tool landing page.
**Constraints:** Desktop-first design, no JavaScript, no AI-generated code, no CSS frameworks.

### 🏗️ Sections Recreated
I successfully cloned the following sections:
1.  **Sticky Navigation Bar:** with glassmorphism effect (`backdrop-filter`).
2.  **Hero Section:** Huge typography with negative letter spacing and precise alignment.
3.  **Trusted By:** Logo grid with opacity filters.
4.  **Feature Blocks:** Alternating text/image layouts using Flexbox.
5.  **Testimonials Grid:** A 3-column masonry-style grid using CSS Grid.
6.  **"Stay on the Frontier":** Feature cards with hover effects.
7.  **Changelog:** List of recent updates with semantic `<time>` tags.
8.  **Careers & Highlights:** Call-to-action sections with specific button styling.
9.  **Footer:** Multi-column layout with links and copyright info.

---

## 🎨 Design System

### Fonts
- **Primary Font:** `Inter` (Sans-serif) - Used for all headings and body text to match the original site's clean, developer-focused aesthetic.

### Color Palette
I used CSS Variables (`:root`) to maintain consistency:

| Color | Hex Code | Usage |
| :--- | :--- | :--- |
| **Background Black** | `#0a0a0a` | Main page background |
| **Card Background** | `#121212` | Testimonials, feature cards |
| **Text White** | `#ededed` | Headings, primary text |
| **Text Muted** | `#8b8b8b` | Subtitles, footer links |
| **Border Color** | `#27272a` | Subtle borders on cards/images |
| **Accent Blue** | `#3b82f6` | Links and highlights |

---

## 💻 Technical Highlights

- **Semantic HTML5:** Used `<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<figure>`, and `<time>` tags for better accessibility and SEO.
- **Modern CSS:**
  - `backdrop-filter: blur(12px)` for the sticky header.
  - `grid-template-columns: repeat(3, 1fr)` for card layouts.
  - `gap` property for consistent spacing.
  - `letter-spacing: -0.03em` to mimic the premium typography style.

---

![Landing Page Preview] (assets/screenshots/screenshot.png.png)


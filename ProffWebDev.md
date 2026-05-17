# Professional Web Development Learning Plan: HTML & CSS

This plan is designed to take you out of "tutorial hell" and build your confidence from the ground up, the way professionals and top engineering students learn. It focuses heavily on understanding the *why* behind concepts, establishing strong fundamentals, and learning through doing rather than just watching.

## The Core Philosophy
1. **Build over Binge:** You will spend 20% of your time reading/learning and 80% building.
2. **Read the Docs (RTFM):** Get comfortable using MDN Web Docs as your primary source of truth instead of YouTube videos.
3. **Semantic First:** HTML isn't just about putting things on a screen; it's about giving meaning to content.
4. **CSS Architecture:** We won't just write CSS; we will write maintainable, scalable CSS.

---

## Phase 1: The Foundation - Semantic HTML & Accessibility

Before making things look pretty, we need a robust skeleton. This phase focuses entirely on raw HTML.

### Key Concepts to Master:
- **Document Structure:** `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<meta>` tags.
- **Semantic Tags:** Why use `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, and `<footer>` instead of just `<div>` everywhere.
- **Text Formatting:** `<h1>` to `<h6>`, `<p>`, `<strong>`, `<em>`, `<blockquote>`, lists (`<ul>`, `<ol>`, `<li>`).
- **Forms & Inputs:** Deep dive into `<form>`, `<input>` types, `<label>` (crucial for accessibility), `<select>`, `<button>`.
- **Media:** `<img>` (always use `alt` tags), `<audio>`, `<video>`, `<picture>` for responsive images.
- **Accessibility (a11y) Basics:** ARIA roles (briefly), tab indexing, semantic meaning for screen readers.

### 🛠️ Projects for Phase 1:
1. **A Text-Only Wikipedia Page:** Recreate a simple Wikipedia article using only HTML. Focus on correct headings, paragraphs, lists, and links.
2. **A Comprehensive Registration Form:** Build a complex form with various input types (text, email, password, radio, checkbox, date), proper labels, and basic HTML validation (`required`, `min`, `max`).

---

## Phase 2: The Engine - Core CSS & Layouts

Now we add style. We won't touch frameworks. We will master pure, vanilla CSS.

### Key Concepts to Master:
- **Selectors & Specificity:** Classes, IDs, attribute selectors, pseudo-classes (`:hover`, `:focus`, `:nth-child`), and understanding how specificity weight works (the cascade).
- **The Box Model:** The most important concept in CSS. Understanding `content`, `padding`, `border`, and `margin`. `box-sizing: border-box`.
- **Display Properties:** `block`, `inline`, `inline-block`, `none`.
- **Positioning:** `static`, `relative`, `absolute`, `fixed`, `sticky`. Understanding stacking contexts (`z-index`).
- **Typography & Colors:** Web safe fonts, Google Fonts, `rem` vs `em` vs `px`, HEX, RGB, HSL.
- **Flexbox (1D Layout):** Master alignment, justification, wrapping, and flex item properties (`flex-grow`, `flex-shrink`, `flex-basis`).

### 🛠️ Projects for Phase 2:
1. **CSS Art / Single Div Project:** Create a simple shape or icon using only one `<div>` and CSS magic (border-radius, box-shadows, pseudo-elements `::before`, `::after`).
2. **Flexbox Product Card:** Design a beautiful, responsive product card with an image, title, description, price, and a "Buy" button.
3. **A Navigation Bar:** Build a responsive top navigation bar with a logo on the left and links on the right using Flexbox.

---

## Phase 3: Professional Grade - Advanced CSS & Architecture

This is where you go from amateur to professional.

### Key Concepts to Master:
- **CSS Grid (2D Layout):** Defining grids, `grid-template-columns`, `grid-template-rows`, `gap`, placing items spanning rows/columns.
- **Responsive Web Design:** Media queries (`@media`), mobile-first approach, responsive units (`vw`, `vh`, `%`).
- **CSS Variables (Custom Properties):** Defining `--primary-color` and using them for theming (like dark mode).
- **Animations & Transitions:** `transition-property`, `transition-duration`, `timing-functions`. Keyframe animations (`@keyframes`) for more complex movements.
- **CSS Methodology:** Introduction to BEM (Block Element Modifier) or similar naming conventions to keep your CSS clean and maintainable.

### 🛠️ Projects for Phase 3:
1. **CSS Grid Dashboard Layout:** Build the structural layout of a web app dashboard (Sidebar, Header, Main Content Area, Widgets) using Grid.
2. **Dark Mode Toggle:** Build a simple page and use CSS Variables to implement a dark mode switch (requires a tiny bit of JS just to toggle a class on the body, but the logic is all CSS).
3. **Animated Landing Page:** Create a hero section for a startup with subtle entrance animations (fade ins, slide ups) and hover effects on buttons.

---

## Phase 4: Capstone Projects - Tying it All Together

Putting everything into practice without tutorials holding your hand.

### 🛠️ The Capstone Challenges:
1. **Personal Portfolio Website (Single Page):**
   - Semantic HTML5 structure.
   - Fully responsive (Mobile, Tablet, Desktop).
   - Use Flexbox for alignments and Grid for a project gallery.
   - Smooth scrolling navigation.
   - Professional typography and color palette.
2. **Clone a Popular UI:**
   - Choose a well-designed site (e.g., Apple's homepage, a specific Netflix page, or Stripe's landing page) and try to rebuild the visual layout and styling as perfectly as possible using only HTML and CSS. (This is the ultimate test of your layout skills).

---

## User Review Required

Does this structured approach align with how you want to learn? 

> [!IMPORTANT]
> Let me know if you approve this plan! If you do, we can start immediately on **Phase 1, Project 1**, and I will act as your senior engineer/mentor, reviewing your code, asking you questions, and pushing you to find the answers in the documentation.


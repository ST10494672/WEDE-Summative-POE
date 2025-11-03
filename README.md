# Grace & Grounds Coffeehouse Website

## Project Information  
- **Student:** Jordan Knipe  
- **Student Number:** ST10494672  
- **Course:** Web Development  
- **Institution:** Varsity College  
- **Submission Date:** November 2025  

## Project Title  
**Grace & Grounds Coffeehouse: A Faith-Based Community Café Website — Part 2: External Styling & Responsive Design**

## Overview  
Grace & Grounds Coffeehouse is a faith-centered café in Cape Town, founded by Sarah and Mark Johnson in 2023.  
The café provides a welcoming space where guests can enjoy quality coffee, connect with others, and experience God’s grace through hospitality, prayer, and community events.  

This second phase of the website project refactors the site to use a **single external CSS stylesheet** (`styles.css`).  
The update improves:  
- Styling consistency  
- Maintainability  
- Full responsiveness across mobile, tablet, and desktop  
- Accessibility compliance (WCAG-aligned)  
- SEO and performance best practices  

All while preserving the original mission, content, and user experience.

grace-and-grounds-website/
├── index.html # Home page (hero section + CTA)
├── about.html # About Us, Mission, Vision, Team
├── menu.html # Hot/Cold drinks, Vegetarian option
├── enquiry.html # Volunteer roles, Donation breakdown, Contact form
├── contact.html # Location, Map, Contact details
└── css/
└── styles.css # Centralized stylesheet for all pages

## Mission and Vision  
**Mission**  
- To provide a peaceful, inclusive space where people connect and experience God’s love — both in person and online.  

**Vision**  
- To build a thriving, faith-centered digital community where every interaction reflects grace, generosity, and purpose.

## Goals for Part 2  
- Eliminate inline and internal CSS; use one external `styles.css` file  
- Ensure visual and structural consistency across all five pages  
- Implement responsive design using `rem`, `%`, Flexbox, and media queries  
- Improve accessibility with semantic HTML, ARIA labels, focus indicators, and skip navigation  
- Optimize performance (font loading, lazy image loading)  
- Create a complete, production-ready page structure (header, main, footer)

## Key Performance Indicators (KPIs)  
- Growth in unique visitors per month  
- Event RSVPs and attendance  
- Email sign-ups for devotionals  
- Volunteer applications via `enquiry.html`  
- Online donations and engagement  

## Changelog (Part 2 Updates)

### Major Enhancements
- **Added semantic `<footer>`** to all pages with contact info, copyright, and navigation  
- **Implemented skip-to-main-content link** for keyboard accessibility (WCAG 2.1 AA)  
- **Added `id="main-content"`** to `<main>` for skip link target  
- **Optimized Google Fonts** with `&font-display=swap` for faster text rendering  
- **Added favicon placeholder** for brand consistency  
- **Enhanced form accessibility**: `autocomplete`, proper labels, and focus styles  
- **Refined mobile menu**: DOM-safe JavaScript with `DOMContentLoaded` and null checks  
- **Ensured white tagline visibility** in hero section with proper contrast and centering  

### Structural & Maintenance Improvements
- Removed all internal `<style>` blocks from HTML files  
- Centralized all styling in `css/styles.css`  
- Verified correct file paths (`css/styles.css`) to prevent 404 errors  
- Standardized section layout using `.section` class consistently  
- Added meta description tags to all pages for SEO  

### Bug Fixes & Content Updates
- Fixed broken image URLs (removed leading whitespace in `src`)  
- Corrected navigation active states per page  
- Fixed malformed lists and semantic structure in `menu.html`  
- Added missing team member (Sarah Johnson) to `about.html`  
- Updated outdated link (`events.html` → `enquiry.html`)  
- Verified all internal links and anchor references  

### Accessibility & Compliance
- Added `aria-label="Main navigation"` to `<nav>`  
- Added `aria-label="Toggle navigation menu"` to mobile toggle  
- Implemented visible focus styles for all interactive elements  
- Used semantic heading hierarchy (`h1` → `h2` → `h3`)  
- Ensured sufficient color contrast (text vs. background)

## References (Updated)

**Image Sources**  
- Unsplash. (2023). Coffee shop interior. (https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)  
- Borba, J. (2023). Man in suit looking at camera. Unsplash. (https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&auto=format&fit=crop&w=150&q=80)  
- wocintechchat.com. (2023). Woman smiling at camera. Unsplash. (https://images.unsplash.com/photo-1594736798588-49fa1f3da49a?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=150&w=150&q=80)  

**Map Embed**  
- Google. (n.d.). Google Maps – Cape Town, South Africa.(https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d38777.41155623949!2d18.4239883!3d-33.9252767!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc62e388879083%3A0x79d395361a5120!2sCape%20Town%20City%20Bowl!5e0!3m2!1sen!2sza!4v1720000000000!5m2!1sen!2sza)  

**AI Assistance**  
- Alibaba Cloud. (2024). Qwen (Version 2.5) [Large language model].
- OpenAI. (2025). ChatGPT (June 2025 version) [Large language model]. 

## How to Test Locally  
1. Ensure the folder structure matches the project layout above  
2. Open any `.html` file in a modern browser (Chrome, Firefox, Edge)  
3. Use **Live Server** (VS Code extension) for best results (avoids file protocol issues)  
4. Check browser console for 404 errors (e.g., missing `styles.css` or images)  
5. Resize the window to test responsive breakpoints (mobile: <768px, tablet: 769–1024px)  
6. Press `Tab` to navigate — verify skip link appears and focus styles are visible  
7. Test mobile menu toggle (☰) on narrow screens  
8. Submit the form on `enquiry.html` (note: `action="#"` is for frontend only; backend required for real submissions)




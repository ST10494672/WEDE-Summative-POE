# Grace & Grounds Coffeehouse Website — Part 2  

##  Project Information  
- **Student:** Jordan Knipe  
- **Student Number:** ST10494672  
- **Course:** Web Development  
- **Institution:** Varsity College  
- **Submission Date:** April 2025  

##  Project Title  
**Grace & Grounds Coffeehouse: A Faith-Based Community Café Website — Part 2: External Styling & Responsive Design**  

##  Overview  
Grace & Grounds Coffeehouse is a faith-centered café in Cape Town, founded by Sarah and Mark Johnson in 2023.  
The café provides a welcoming space where guests can enjoy quality coffee, connect with others, and experience God’s grace through hospitality, prayer, and community events.  

This second phase of the website project refactors the site to use a **single external CSS stylesheet**.  
The update improves:  
- Styling consistency  
- Maintainability  
- Responsiveness across all devices  

All while keeping the original mission and structure intact.  

grace-and-grounds-website/
├── index.html           # Home page
├── about.html           # About Us & Team
├── menu.html            # Menu & Vegetarian Option
├── enquiry.html         # Serve & Give (Volunteer + Donate)
├── contact.html         # Locations, Map, Contact Form
└── css/
    └── styles.css       # Single external stylesheet — controls ALL styling

##  Mission and Vision  
**Mission**  
- To provide a peaceful, inclusive space where people connect and experience God’s love — both in person and online.  

**Vision**  
- To build a thriving, faith-centered digital community where every interaction reflects grace, generosity, and purpose.  

##  Goals for Part 2  
- Use an external CSS file (`styles.css`) to remove inline duplication  
- Apply consistent typography, colors, and layout across all five pages  
- Ensure full responsiveness with media queries and relative units (`rem`, `%`)  
- Enhance accessibility with semantic HTML, focus states, and ARIA-friendly elements  
- Simplify maintenance with centralized styling in one file  

##  Key Performance Indicators (KPIs)  
- Growth in unique visitors per month  
- Event RSVPs and attendance  
- Email sign-ups for devotionals  
- Volunteer applications  
- Online donations  

##  Changelog (Part 2 Updates)  

**Changes Made from Part 1:**  
- Removed all internal `<style>` blocks from 5 HTML files  
- Created and linked external `styles.css` file  
- Fixed broken links (e.g., `events.html` → `enquiry.html`)  
- Added missing team member (Sarah Johnson) to `about.html`  
- Corrected malformed `<ul>` structure in `menu.html`  
- Added mobile navigation toggle script to all pages  
- Improved accessibility: focus states, autocomplete attributes, ARIA labels  
- Applied consistent spacing, fonts, and colors using rem-based scale  
- Optimized image URLs (removed leading whitespace)  
- Added meta description tags for SEO  
- Verified responsive behavior on mobile/tablet/desktop  

**Issues Resolved:**  
- CSS not loading → fixed by ensuring correct folder/file path (`css/styles.css`)  
- Mobile menu not working → added `#menuToggle` and script to all pages  
- Broken list items → fixed `<ul>` nesting in `menu.html`  
- Missing content → added Sarah’s bio and corrected CTA links  

##  References (Updated)  

**Image Sources**  
- Unsplash. (2023). Coffee shop interior. [Link](https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)  
- Borba, J. (2023). Man in suit looking at camera. Unsplash. [Link](https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&auto=format&fit=crop&w=150&q=80)  
- wocintechchat.com. (2023). Woman smiling at camera. Unsplash. [Link](https://images.unsplash.com/photo-1594736798588-49fa1f3da49a?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=150&w=150&q=80)  

**Map Embed**  
- Google. (n.d.). Google Maps – Cape Town, South Africa. [Link](https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d38777.41155623949!2d18.4239883!3d-33.9252767!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcc62e388879083%3A0x79d395361a5120!2sCape%20Town%20City%20Bowl!5e0!3m2!1sen!2sza!4v1720000000000!5m2!1sen!2sza)  

**AI Assistance**  
- Alibaba Cloud. (2024). Qwen (Version 2.5) [Large language model]. Available at: [https://qwen.ai](https://qwen.ai)  
- OpenAI. (2025). ChatGPT (June 2025 version) [Large language model]. Available at: [https://chatgpt.com](https://chatgpt.com)  

##  How to Test Locally  
1. Ensure folder structure matches your project setup  
2. Open any `.html` file in a browser (drag into Chrome/Firefox or use Live Server)  
3. Check the console for 404 errors (if CSS doesn’t load)  
4. Resize window to test responsiveness  
5. Tab through form fields to verify focus states  
6. Click the mobile menu icon (☰) to test toggle functionality  



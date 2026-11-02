# Ndzalo Ra Rhulani NPC — Web Development Project (WEDE5020)

**Student Name:** Vutlharhi Gift Magagula  
**Student ID:** ST10535839  
**Module:** Web Development (WEDE5020)  
**Qualification:** Diploma in Information Technology in Software Development (DISD1)  
**Institution:** Rosebank College (Mbombela Campus)  
**Live Site URL:** [https://<YOUR-GITHUB-USERNAME>.github.io/WEDE5020/](https://<YOUR-GITHUB-USERNAME>.github.io/WEDE5020/)  

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Organisation Details](#organisation-details)
3. [Target Audience & User Personas](#target-audience--user-personas)
4. [Website Architecture & Navigation](#website-architecture--navigation)
5. [Responsive Design & Screenshots](#responsive-design--screenshots)
6. [Functionality & Form Validation](#functionality--form-validation)
7. [SEO Implementation](#seo-implementation)
8. [Changelog & Revision History](#changelog--revision-history)
9. [Deployment Instructions](#deployment-instructions)
10. [Reference List](#reference-list)

---

## Project Overview
Ndzalo Ra Rhulani NPC is a Non-Profit Company (NPC) established in 2026 in Nelspruit (Mbombela), Mpumalanga. The organisation was created to address the digital divide by offering accessible web presence setup, digital literacy guidance, and Google Business Profile assistance to local small, medium, and micro-enterprises (SMMEs).

This website serves as the primary digital portal for the organisation, enabling small business owners to apply for digital support, allowing volunteers to sign up, and offering corporate social investment (CSI) sponsors a platform to partner with the organisation.

---

## Organisation Details
- **Organisation Name:** Ndzalo Ra Rhulani NPC
- **Registration Type:** Non-Profit Company (NPC)
- **Founder:** Vutlharhi Gift Magagula
- **Location:** 19 Hope St, Mbombela, 1201, Mpumalanga, South Africa
- **Contact Email:** info@ndzalorarhulani.org.za / contact@ndzalorarhulani.org.za
- **Contact Phone:** 013 645 3000

---

## Target Audience & User Personas
The website caters to three core user groups across Mpumalanga:

1. **Small Business Owners (Aged 25–55):** Local artisans, traders, and service providers seeking an affordable, non-technical way to establish an online presence.
2. **Sponsors & CSI Donors:** Corporate representatives and philanthropic individuals seeking verified community upliftment projects to fund.
3. **Community Volunteers & Youth:** Local IT students and tech-savvy youth seeking practical field experience while assisting local SMMEs.

---

## Website Architecture & Navigation
The website consists of five core HTML pages linked with semantic navigation:

- `index.html`: Home page featuring the organisation's mission, impact metrics, and service summaries.
- `about_us.html`: Detailed history, mission, vision, values, and community overview.
- `our_services.html`: Breakdown of the three core offerings (Starter Web Setup, Digital Literacy Guidance, Google Business Profile Assistance).
- `enquires.html`: Dynamic enquiry form for business owners, volunteers, and sponsors with real-time JavaScript validation.
- `contact_us.html`: Physical location details, embedded Google Map, contact information, and social media links.

---

## Responsive Design & Screenshots

### Desktop View
*(Insert Desktop Screenshot Here)*  
*Figure 1.1: Desktop Navigation and Layout (1200px+)*

### Tablet View
*(Insert Tablet Screenshot Here)*  
*Figure 1.2: Tablet Grid Adaptation (768px - 1024px)*

### Mobile View
*(Insert Mobile Screenshot Here)*  
*Figure 1.3: Mobile Navigation Toggle and Stacked Layout (360px - 600px)*

---

## Functionality & Form Validation
Client-side interactivity and validation are handled by `js/main.js`:

- **Mobile Menu Toggle:** Dynamically toggles navigation visibility on viewports smaller than 600px.
- **Enquiry Form Validation (`enquires.html`):** Validates full name (min 2 characters), email structure using standard regular expressions (`/^[^\s@]+@[^\s@]+\.[^\s@]+$/`), and message length (min 10 characters). Displays clear inline error state indicators and auto-clears fields on valid submission.
- **Contact Form Validation (`contact_us.html`):** Ensures all fields are populated before giving user confirmation feedback.

---

## SEO Implementation
Technical and on-page Search Engine Optimisation (SEO) includes:

- **Meta Tags:** Customized `<title>`, `description`, `keywords`, and `author` tags across all five pages.
- **`robots.txt`:** Placed in the root directory to guide search engine crawlers and point to the XML sitemap.
- **`sitemap.xml`:** XML sitemap referencing all five site URLs with updated modification dates and priority levels.

---

## Changelog & Revision History

### Part 1 — Initial Design & Planning
- Formulated site structure, wireframes, color palette, and core text content.
- Drafted initial HTML layout for home and about pages.

### Part 2 — Multi-Page Implementation & Styling
- Expanded project to 5 complete HTML pages.
- Standardized navigation and footer structures across all pages.
- Created external stylesheet (`css/style.css`) using CSS variables, grid system, and media queries for responsiveness.

### Part 3 — Enhancements, Validation & Deployment
- Implemented `js/main.js` for mobile menu toggling and form validation.
- Added `robots.txt` and `sitemap.xml` to the project root folder.
- Fixed case-sensitivity in filenames (`index.html`, `about_us.html`, `our_services.html`, `enquires.html`, `contact_us.html`) to ensure compatibility with Linux web servers.
- Resolved SVG social link overlay and click issues on `contact_us.html`.
- Deployed final site to GitHub Pages / Netlify.

---

## Deployment Instructions

1. **Clone Repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<YOUR-GITHUB-USERNAME>/WEDE5020.git



   REFERENCE LIST:
Duckett, J., 2011. HTML and CSS: Design and Build Websites. Indianapolis: John Wiley & Sons.

MDN Web Docs, 2026. Client-side form validation. Available at: https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_forms_through_JavaScript [Accessed 1 November 2026].

MDN Web Docs, 2026. Sitemaps and robots.txt. Available at: https://developer.mozilla.org/en-US/docs/Glossary/Robots.txt [Accessed 1 November 2026].

World Wide Web Consortium (W3C), 2026. Web Content Accessibility Guidelines (WCAG) 2.1. Available at: https://www.w3.org/TR/WCAG21/ [Accessed 1 November 2026].

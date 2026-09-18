# WEDE5020 PoE

# Smithfield Primary School Website

## Overview
This project is a static, responsive website developed for **Smithfield Primary School**, a Quintile 2 public primary school located in Skoolstraat, Rietpoort, Smithfield, Free State. The website serves as a digital hub for the local community, providing essential information about the school's history, academic phases, admissions process, and contact details.

## Pages Included
The website consists of five primary HTML pages:
- **`index.html` (Home):** A welcoming landing page featuring the school emblem, a call-to-action for 2027 enrollment, and the latest announcements.
- **`about.html` (About Us):** Details the school's history, its mission and vision statements, and introduces the school's principal, Mr. H. Pietersen.
- **`services.html` (Admissions & Academics):** Outlines academic phases (Foundation, Intermediate, and Senior), provides downloadable enrollment resources (PDF forms and calendars), and details school uniform guidelines.
- **`enquiry.html` (Enquiry):** A dedicated form for community members to reach out regarding volunteer applications, sponsorships, general information, and admissions.
- **`contact.html` (Contact Us):** Contains the school's contact information (phone, email, office hours), a direct messaging form, and embedded Google Maps for both the main campus and the Xhariep District Education Office.

## Features
- **Responsive Design:** Utilizes standard viewport meta tags to ensure the site is accessible and readable on both mobile devices and desktops.
- **Semantic HTML5:** Built using modern, semantic HTML tags (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`) for better structure, SEO, and accessibility.
- **Interactive Forms:** Includes structured web forms for structured enquiries and direct contact messaging.
- **Embedded Maps:** Integrates Google Maps iframes to help visitors easily locate the school campus and the regional district office.
- **Downloadable Resources:** Provides direct links to download essential PDF documents.

## Directory Structure (Assumed based on source paths)
- `/` - Root directory containing all HTML files (`index.html`, `about.html`, `services.html`, `enquiry.html`, `contact.html`).
- `/css/` - Contains the `styles.css` file for external styling.
- `/images/` - Contains images used across the site (e.g., emblem, staff photos, facility photos).
- `/documents/` - Contains downloadable PDF files for parents.

## Technologies Used
- **HTML5:** For the structural foundation of the website.
- **CSS3:** External stylesheet (`css/styles.css`) for consistent styling and layout across all pages.

## How to Run
This is a static HTML website and does not require a local backend server or complex build tools to view.
1. Download or clone the project repository to your local machine.
2. Ensure the directory structure matches the required folders (`css`, `images`, `documents`).
3. Open `index.html` in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari) to navigate the site.

## License and Copyright
&copy; 2026 Smithfield Primary School. All Rights Reserved.

PART 2 

# Smithfield Primary School Website

## Project Overview
This repository contains the front-end source code for the official website of Smithfield Primary School, located in the Mohokare local municipality, Free State. The project is a fully responsive, multi-page web application built using semantic HTML5 and modern CSS3 layout techniques. 

The primary goal of this project is to provide the local community with accessible information regarding admissions, school history, and contact details, while ensuring the platform functions seamlessly across mobile, tablet, and desktop devices.

## Features
* **Semantic Structure:** Built with clean, accessible HTML5 tags (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
* **Responsive Layouts:** Utilizes a combination of CSS Flexbox for navigation components and CSS Grid for complex content structures (e.g., news cards, location maps).
* **Interactive Forms:** Includes structured contact and community enquiry forms with appropriate input types and fieldsets.
* **Embedded Maps:** Integrates Google Maps iframes to display the main school campus and regional district office.
* **Mobile-First Adaptation:** Implements media queries to reflow multi-column grids into single-column layouts on devices narrower than 768px.

## File Structure
``text
/
├── index.html          # Homepage with hero image and latest announcements
├── about.html          # School history, mission, vision, and staff profiles
├── services.html       # Admissions information, academic phases, and uniform guidelines
├── enquiry.html        # Community volunteer and sponsorship form
├── contact.html        # Contact details, direct messaging form, and embedded maps
├── css/
│   └── styles.css      # External stylesheet containing all design and responsive logic
├── images/             # Directory for site assets and responsive images
└── documents/          # Downloadable PDFs (e.g., enrollment forms, calendars)

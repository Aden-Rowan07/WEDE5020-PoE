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

PART 3
Website Project: Smithfield Primary School

Student Information

Name: Aden-Rowan Pietersen

Module: WEDE5020w

Institution: The Independent Institute of Education (IIE) - Rosebank College

Project Overview (Complete)

This repository contains the front-end source code for the official website of Smithfield Primary School, located in the Mohokare local municipality, Free State. The project is a fully responsive, multi-page web application built using semantic HTML5, modern CSS3 layout techniques, and vanilla JavaScript.

The primary goal of this project is to provide the local community with accessible information regarding admissions, school history, and contact details, while ensuring the platform functions seamlessly across mobile, tablet, and desktop devices.

Website Goals and Objectives

Establish a professional, centralized digital presence for the school to share official announcements and term dates.

Digitize the distribution of administrative documents (e.g., enrollment forms and fee structures) to reduce physical administrative burdens.

Facilitate direct community engagement by providing structured digital forms for volunteer and sponsorship applications.

Key Features and Functionality

Semantic Structure: Built with clean, accessible HTML5 tags.

Responsive Layouts: Utilizes a combination of CSS Flexbox for navigation components and CSS Grid for complex content structures.

Interactive Forms with Validation: Includes structured contact and community enquiry forms with client-side JavaScript validation and error handling.

Embedded Maps: Integrates Google Maps iframes to display the main school campus and regional district office.

SEO Optimised: Includes on-page metadata, semantic headers, a sitemap.xml, and a robots.txt file for optimal search engine crawling.

File and Folder Structure

/
├── index.html          # Homepage with hero image and latest announcements
├── about.html          # School history, mission, vision, and staff profiles
├── services.html       # Admissions information, academic phases, and uniform guidelines
├── enquiry.html        # Community volunteer and sponsorship form
├── contact.html        # Contact details, direct messaging form, and embedded maps
├── robots.txt          # Search engine crawler instructions
├── sitemap.xml         # XML sitemap for SEO
├── css/
│   └── styles.css      # External stylesheet containing all design and responsive logic
├── js/
│   └── script.js       # Client-side form validation logic
├── images/             # Directory for site assets, responsive images, and testing screenshots
└── documents/          # Downloadable PDFs (e.g., enrollment forms, calendars)



Implementation Details

Part 1: Structure and Content

Developed a 5-page sitemap and created the foundational HTML boilerplates.

Integrated thoroughly researched content specific to Smithfield Primary School.

Part 2: Responsive Design (CSS)

Flexible Layouts: Applied Flexbox to the <header> and CSS Grid to content cards using the repeat(auto-fit, minmax(300px, 1fr)) property to allow seamless reflowing across different screen sizes.

Media Queries: Established a primary breakpoint at 768px to collapse navigation and grid layouts into a mobile-friendly single column.

Responsive Images: Implemented the HTML5 <picture> element with srcset attributes to serve appropriately sized images based on viewport width.

Part 3: Functionality and SEO (JS & Deployment)

JavaScript Validation: Added script.js to intercept form submissions on enquiry.html and contact.html, ensuring all required fields are populated and phone numbers meet length requirements before processing.

SEO: Added title tags, meta descriptions, and keywords to the <head> of all HTML pages. Generated a comprehensive sitemap.xml and robots.txt.

Deployment: Hosted the static site on Netlify.

Live Site URL: file:///C:/Users/JM/OneDrive/Desktop/school/Web%20development/index.html

Responsive Design Testing Evidence

Below is the screenshot evidence demonstrating the website's responsive layout and media query execution across different screen sizes:

(Note to lecturer: Screenshots are located in the /images/ directory)

Desktop View

Tablet View

Mobile View

Changelog

6 August 2026 : Initialized GitHub repository and added initial HTML file structures and directory folders (Part 1).

4 September 2026: Added styles.css file utilizing CSS Grid, Flexbox, and custom variables for site-wide styling (Part 2).

11 September 2026: Implemented media queries targeting max-width: 768px to ensure the layout collapses into a mobile-friendly single column (Part 2).

20 September 2026: Updated HTML <img> tags to utilize the <picture> element and srcset attributes for responsive image loading (Part 2).

11 October 2026 : Added js/script.js to handle interactive client-side form validation and error handling (Part 3).

20 October 2026: Created and configured robots.txt and sitemap.xml in the root directory (Part 3).

2 November : Integrated SEO meta tags into the <head> sections of all HTML files (Part 3).

6 November 2026: Deployed the completed static web application to Netlify (Part 3).

References

Department of Basic Education, 2024. Master List of Schools. [Online] Available at: https://www.datafirst.uct.ac.za/dataportal/index.php/catalog/979/pdf-documentation [Accessed 6 August 2026].

Education South Africa, no date. Schools in SMITHFIELD, Free State. [Online] Available at: https://www.educationsouthafrica.com/schools/free-state/smithfield [Accessed 6 August 2026].

MDN Web Docs, 2025. Client-side form validation. [Online] Available at: https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation [Accessed 12 October 2026].

Netlify, 2026. Deploy your sites. [Online] Available at: https://www.netlify.com/ [Accessed 12 October 2026].

Schools4SA, no date. Smithfield Ps. [Online] Available at: https://www.schools4sa.co.za/school-profile/smithfield-ps/ [Accessed 6 August 2026].
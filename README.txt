KG DIGITAL EXPERT - ANIMATED STATIC WEBSITE
===========================================

A fast, animated, single-page website for KG Digital Expert (Digital Marketing & Graphic Designing).
No build step and no dependencies. It works on any static host (GitHub Pages, Netlify, cPanel, etc.).
To view it, double-click index.html.

FILES
-----
index.html     Main page: header, hero, services marquee, about, 7 services, how we work, call-back form, contact, footer
privacy.html   Privacy Policy
terms.html     Terms & Conditions
styles.css     All styling and animations (colours are CSS variables at the top; they are taken from your logo)
assets/
  logo.svg     Your KG Digital Expert logo (hero, about and footer). It wraps the same
               image as logo.jpg, so it is not a true vector file.
  logo.jpg     Same logo as a plain image (also used for link previews)
  favicon.png  Browser tab icon and header logo (the KG mark from your logo)

DETAILS USED ON THE SITE
------------------------
Business : KG Digital Expert
Phone    : +91 92895 72329 (call and WhatsApp buttons)
Email    : kgdigitalexpert3@gmail.com
Services : Website Development; E-commerce Platform Management (Amazon, Flipkart, Meesho etc.);
           Search Engine Optimization; Google & Meta Ads; Social Media Management;
           Graphic Designing; WhatsApp API & Automation
Privacy and Terms are dated 10 October 2026 and say disputes go to the competent courts in India.

ANIMATIONS
----------
Page-load fade-up in the hero, drifting colour blobs and pixel squares (like your logo), a floating logo card
with a mouse tilt, rotating service name in the hero, scrolling services strip, scroll progress bar,
cards and steps that rise as you scroll, hover effects on cards, buttons, links and contact boxes,
and a moving colour gradient. All animation stops automatically for visitors whose device is set to
"reduce motion".

THE LEAD FORM
-------------
Fields: Name, Phone number, Service you need, Preferred time to contact.
On submit the form checks the fields, then opens WhatsApp with a ready message
to 919289572329 (India code 91 + 9289572329). The visitor presses Send in WhatsApp and the lead
arrives on +91 92895 72329.
Note: this works without any server, but the lead is only delivered if the visitor presses Send.
To change the number, replace 919289572329 in index.html (in the script near the end and in the WhatsApp buttons).

CHOICES MADE FOR YOU (change in the HTML if needed)
---------------------------------------------------
- Service descriptions are short and general. No prices, results, client numbers or ratings are shown,
  because none were provided.
- Preferred-time choices: Morning (9-12), Afternoon (12-4), Evening (4-8), Any time.
- No office address or business hours are shown, because none were given.

HOW IT WORKS
------------
- Top bar with email and phone, sticky header with a Call button; anchor links scroll smoothly to each section.
- On mobile (under 860px) the menu collapses behind a Menu button and a Call / WhatsApp bar stays at the bottom.
- The Outfit font loads from Google Fonts when online; without internet a clean system font is used.
- The footer year updates automatically.

PUBLISHING ON GITHUB PAGES
--------------------------
1. Create a repository and upload all files, keeping the assets folder.
2. In Settings > Pages, choose the main branch and the root folder.
3. Your site will be live at https://USERNAME.github.io/REPOSITORY/

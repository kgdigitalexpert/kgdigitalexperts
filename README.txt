KG DIGITAL EXPERT - STATIC WEBSITE
==================================

A simple, fast, single-page website for KG Digital Expert (digital marketing agency).
No build step and no dependencies. It works on any static host (GitHub Pages, Netlify, cPanel, etc.).
To view it, double-click index.html.

FILES
-----
index.html     Main page: header, hero, about, services, contact, footer
privacy.html   Privacy Policy (template)
terms.html     Terms & Conditions (template)
styles.css     All styling (colours are CSS variables at the top of the file)
assets/
  logo.svg     Your KG Digital Expert logo (header and footer). It wraps the same
               image as logo.jpg, so it is not a true vector file.
  logo.jpg     Same logo as a plain image (also used in the hero and for link previews)
  favicon.png  Browser tab icon (the KG monogram from the logo)

THINGS TO UPDATE
----------------
1. Office address: search for "[Add your office address" in index.html, and "[add your office address]" in privacy.html and terms.html.
2. Dates: replace "[add date]" in privacy.html and terms.html.
3. Payment terms, ownership of work and city for jurisdiction in terms.html: fill in your own wording.
4. Services: the 8 service cards use your list with short descriptions. Edit the wording if you like.
5. Privacy and terms are templates. Have them reviewed before relying on them.
6. No business hours, founding year or client numbers were given, so none are shown. Add them if you want.

HOW IT WORKS
------------
- Sticky header with a Call button; anchor links scroll smoothly to each section.
- On mobile (under 860px) the menu collapses behind a Menu button and a floating "Call now" button appears.
- The WhatsApp buttons open a chat with 9289572329 and a ready message.
  The number is written as 919289572329 (India country code 91). Change it in index.html if needed.
- The footer year updates automatically.

PUBLISHING ON GITHUB PAGES
--------------------------
1. Create a repository and upload all files, keeping the assets folder.
2. In Settings > Pages, choose the main branch and the root folder.
3. Your site will be live at https://USERNAME.github.io/REPOSITORY/

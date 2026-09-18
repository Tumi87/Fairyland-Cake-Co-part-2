# Fairyland-Cake-Co-part-2
Project Overview

A five-page marketing and order-enquiry website for Fairyland Cake Co., a boutique home bakery offering fully custom cakes, cupcakes and dessert spreads for birthdays, weddings, baby showers and other celebrations. The site replaces the business's previous reliance on social media DMs with a structured order enquiry form, a browsable photo gallery, and clear, published pricing.

## Website Goals and Objectives
-Headings and Open Sans for body copy — across every page.
- Provide clear, transparent pricing and ordering timelines up front.
- Deliver a clean, image-led design that works smoothly across desktop,
  tablet and mobile.
-Create a direct online catalogue for custom cake orders.
-Reduce repetitive, unstructured social media enquiries by moving order requests to a proper enquiry form.
-Establish a professional local footprint for the business.
-Present the brand consistently — Pastel Pink (
#F4C2C2), Warm Cream (
#FFFDD0) and Deep Charcoal (
#2C2C2C), with Playfair Display for headings and Open Sans for body copy — across every page.
-Provide clear, transparent pricing and ordering timelines up front.
-Deliver a clean, image-led design that works smoothly across desktop, tablet and mobile.

## Key Features and Functionality
**Sticky, responsive navigation** with a pure-CSS (checkbox-based)
  mobile hamburger menu — no JavaScript required.
- **Homepage hero slideshow** — four cake photos auto-fade on a loop,
  pause on hover, and respect `prefers-reduced-motion` for accessibility.
- **Index page intro paragraph beside the slideshow** — the hero section
  on `index.html` pairs the sliding pictures with an introductory
  paragraph (business tagline + call-to-action buttons to the Contact
  and Menu pages), so visitors get context alongside the visuals as soon
  as the page loads.
- **Order/Contact enquiry form** capturing full name, email, phone, event
  date, occasion, flavour, servings, dietary requirements (gluten-free /
  eggless), theme details and additional notes — replacing informal DM
  ordering with one structured submission.
- **Photo gallery** grouped by occasion (Birthdays, Weddings, Baby
  Showers), with hover/focus captions on each image.
- **Menu & pricing page** listing daily treats and celebration cake
  base prices, plus dietary customisation and ordering-timeline notes.
- **Contact & locations section** with two embedded pickup-location maps
  (Randburg and Sandton), email, phone and WhatsApp links.
- Consistent, reusable card/button/form styling and hover/focus states
  across all five pages.
-Sticky, responsive navigation with a pure-CSS (checkbox-based) mobile hamburger menu — no JavaScript required.
-Homepage hero slideshow — four cake photos auto-fade on a loop, pause on hover, and respect prefers-reduced-motion for accessibility.
-Order/Contact enquiry form capturing full name, email, phone, event date, occasion, flavour, servings, dietary requirements (gluten-free / eggless), theme details and additional notes — replacing informal DM ordering with one structured submission.
-Photo gallery grouped by occasion (Birthdays, Weddings, Baby Showers), with hover/focus captions on each image.
-Menu & pricing page listing daily treats and celebration cake base prices, plus dietary customisation and ordering-timeline notes.
-Contact & locations section with two embedded pickup-location maps (Randburg and Sandton), email, phone and WhatsApp links.
-Consistent, reusable card/button/form styling and hover/focus states across all five pages.

## Timeline and Milestones
## Milestone	Status
Organisation chosen & proposal approved (12 August 2026r)	Complete
Part 1 — Sitemap, file structure, HTML pages	Submitted
Part 1 — Feedback received	Received
Part 2 — Feedback corrections	In progress (see Changelog)
Part 2 — CSS styling (desktop)	Complete
Part 2 — Responsive design (tablet/mobile)	Complete

 ## Sitemap
Home (index.html)
├── About Us (about.html)
├── Menu & Pricing (menu.html)
├── Gallery (gallery.html)
└── Order / Contact (contact.html)
File and Folder Structure
root/
├── index.html
├── about.html
├── menu.html
├── gallery.html
├── contact.html
├── style.css
└── gallery/          (cake photography used across all pages)

images links


## Changelog
Part 2 — [21 September 2026]
Fixed: GitHub repository link was not accessible from Part 1 — corrected repository visibility/collaborator access so the link now opens correctly.
Built out the full external stylesheet (style.css): CSS reset, design tokens (colour palette, typography, spacing scale), base styles, and reusable component styling (cards, buttons, forms, nav).
Implemented the homepage image slideshow with CSS keyframe animation, hover-to-pause, and a reduced-motion fallback.
Added hover/focus caption reveal on gallery images.
Built the full order enquiry form on the Contact page (occasion, flavour, servings, dietary requirements, theme, event date).
Implemented responsive design with breakpoints at 1024px (tablet), 768px (mobile — nav collapses to toggle menu) and 480px (small mobile).
GitHub link (https://github.com/Tumi87/Fairyland-Cake-Co.) 

 ## Part 1 — [ 14 August 2026]
-Target organisation selected: Fairyland Cake Co. (small business — home bakery).
-Business proposal completed and approved (4 September).
-Initial sitemap and file structure created.
-Built the five core HTML pages (index, about, menu, gallery, contact) with semantic structure and working navigation.
-Known Issues / Next Steps
 -Confirm css/, js/, images/ subfolders match the brief exactly (currently images sit in a gallery/ folder).
 -Add srcset/sizes or <picture> for responsive image loading on key photos (hero slideshow, gallery).
- Add screenshot evidence of desktop/tablet/mobile testing to this README.
- Double-check the WhatsApp link phone number is formatted correctly (no spaces) for the wa.me link to work.
- Confirm footer phone numbers are consistent across all five pages.
## Page Content Breakdown

### Homepage (index.html)
- **Eyebrow text:** "Handcrafted since 2021"
- **Heading:** "Custom cakes made for your celebration"
- **Paragraph:** intro copy describing Fairyland Cake Co. as a boutique
  home bakery and inviting visitors to browse the menu, gallery, and send
  an enquiry
- **Two call-to-action buttons:** "Start an order enquiry" and "View menu
  & pricing"
- **Picture slideshow:** four cake photos (main cakes, cupcakes, rainbow
  cake, red velvet) that auto-fade on a loop and pause on hover
- Below the hero: a 3-card "Why Fairyland" feature section and a final
  call-to-action banner

### About Us (about.html)
Founding story, mission & vision, who the bakery serves, a 3-card values
section, and a customer testimonial.

 
## References
Adobe Acrobat. n.d. How to write a business proposal. Available at: https://www.adobe.com/acrobat/business/resources/how-to-write-a-business-proposal.html [Accessed 5 August 2026].
Visual Studio Code. n.d. Code editing. Redefined. Available at: https://code.visualstudio.com/ [Accessed 9 August 2026].
GitHub. n.d. Pricing for every developer. Available at: https://github.com/pricing [Accessed 5 August 2026].
HostAfrica. n.d. Website builder. Available at: https://hostafrica.co.za/website-builder/ [Accessed 11 August 2026].
HubSpot Marketing. 2022. How to write a business proposal step-by-step with FREE template. YouTube video. Available at: https://www.youtube.com/watch?v=2j3cKR28r5Q [Accessed 6 August 2026].
OneCompiler. n.d. HTML Compiler. Available at: https://onecompiler.com/html/44yefssrx [Accessed 8 August 2026].
Pinterest. n.d. Wedding and baby shower cakes. Available at: https://www.pinterest.com [Accessed 9 August 2026].
W3Schools. n.d. How to make a website for business. Available at: https://www.w3schools.com/howto_website_business.asp [Accessed 28 August 2026].
W3Schools. n.d. W3Schools online web tutorials. Available at: https://www.w3schools.com [Accessed 3 August 2026].
Google Fonts. n.d. Playfair Display & Open Sans. Available at: https://fonts.google.com/ [Accessed: 16 September 2026].
githublink https://github.com/Tumi87/Fairyland-Cake-Co-part-2





<img width="1275" height="879" alt="cakefairylanf" src="https://github.com/user-attachments/assets/83bfa1ac-39d1-469d-b035-85c09e8d37b2" />
<img width="658" height="803" alt="fairylanddd" src="https://github.com/user-attachments/assets/ba8708a6-eaa4-4deb-a7a8-65c1b383bab2" />
<img width="592" height="764" alt="savecake" src="https://github.com/user-attachments/assets/bb2f5a02-8951-4ba0-a889-c827a10f64d6" />
<img width="587" height="922" alt="cakefary" src="https://github.com/user-attachments/assets/5a2b234c-efe4-40f1-a2b7-f7a844ffdccb" />

<img width="592" height="708" alt="Screenshot 2026-09-18 142115" src="https://github.com/user-attachments/assets/87f3ca92-60bc-47fb-9464-c96254b29cd2" />
<img width="1126" height="773" alt="website cake 1" src="https://github.com/user-attachments/assets/1c055c27-7533-4164-afe3-9d8454e45692" />
<img width="1126" height="774" alt="Screenshot 2026-09-18 141620" src="https://github.com/user-attachments/assets/e60bcff1-e478-41ea-a9c9-5f5e98c03103" />
<img width="1106" height="899" alt="Screenshot 2026-09-18 141736" src="https://github.com/user-attachments/assets/ad6baf22-88dc-4dad-b3a7-9fbe382bf310" />
<img width="894" height="791" alt="Screenshot 2026-09-18 141953" src="https://github.com/user-attachments/assets/5c21da32-25f6-4f5a-b600-d38a98b0c0cf" />
<img width="941" height="396" alt="Screenshot 2026-09-18 141551" src="https://github.com/user-attachments/assets/521d411d-e79f-4e6c-93d9-458d59a1841d" />


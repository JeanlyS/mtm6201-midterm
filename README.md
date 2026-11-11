# JS0PX — MTM6201 Midterm

This is a 4 page responsive photography and videography website that follows the overall layout of the LaslesVPN Figma design, but the content and colours were changed to fit my own photography.

## Pages

- `index.html` — Home. Uses the LaslesVPN section order: navigation, hero, 3 stats, features, 3 pricing cards, large feature image, three project highlights, contact callout and footer.
- `pricing.html` — Pricing/services. Three different types of photography projects with a contact link for quotes.
- `gallery.html` — Gallery. A responsive grid of my automotive, event, Porsche, private shoot and landscape photos.\n- `about.html` — About and contact, with some selected automotive, event and landscape photos.

## Original Design / Attribution

**Original Figma design:** LaslesVPN Landing Page  
**Original designer:** Didi Kurniawan  
**Figma community file:** https://www.figma.com/community/file/858999227165747995

The original mockup is saved in `images/laslesvpn-original-mockup.png`.

## What I changed

The original design is for a VPN company, so I used the same basic section order and overall layout but adapted it for JS0PX photography and videography. The illustrations were replaced with my own photos, the colour palette became charcoal and copper, the VPN packages became photography services and the world map became a wide landscape photo. I kept the three cards in the testimonials spot but used project descriptions instead of making up reviews.

## Images

Photos are my own images. Every photo used on the site has 2 optimized WebP files, a small one and a large one, and the HTML uses `srcset` and `sizes` to let the browser choose which file to load. The original photos were resized for web use. The mockup image is the one exception since its there as the required reference, not displayed in the webpage.

## Techniques

Plain HTML and CSS only, with CSS Grid, Flexbox, custom properties, `::before`, hover transitions, keyframe animations, responsive media queries, skip links, meaningful alternative text, and Schema.org microdata. No Bootstrap or JavaScript.

## Important

Prices are not listed as actual rates, since shoots depend on the location, project and deliverables. Porsche Mark Motors, Cars & Coffee Ottawa and JerryG80 are shown as project/work highlights, **not** claimed customer testimonials or quotes.

## Publishing

The files in this folder can be uploaded into the `mtm6201-midterm` GitHub repository. Enable GitHub Pages from the repository settings, with the root folder as the site source. Please validate the final deployed HTML and CSS and test the images, links and responsive layout before submitting.

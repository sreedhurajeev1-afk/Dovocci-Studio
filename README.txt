DOVOCCI — CLEAN HTML/CSS ONLY EDITION

START
Extract the ZIP completely. Open index.html, or upload this entire folder to a static web host. Keep styles.css and assets/ beside index.html. No JavaScript, framework or build step is required.

EDIT
index.html: services, copy, links and image paths.
styles.css: one clean stylesheet, scoped to #dovocci-site. Shared colours are defined on that wrapper. Responsive overrides are grouped at 1024px and 700px.
assets/: 77 local photos/logo files. Photographs use object-fit:contain to preserve the whole image.

IMPORTANT FOR THE DEVELOPER
Replace the previous stylesheet completely; do not append this stylesheet to the old one. Do not merge old HTML sections into this page. The HTML wrapper nesting has been corrected.

For WordPress, Elementor or another existing theme: keep the complete #dovocci-site wrapper and load styles.css. Upload assets and update image/link URLs to their actual uploaded locations. Relative assets/... URLs resolve relative to the page URL; pasting HTML alone into a CMS does not upload images. Missing-image icons are an asset URL/loading issue, not a CSS layout issue.

All selectors are scoped to #dovocci-site to avoid normal generic theme conflicts. This was tested against deliberately conflicting generic heading, paragraph, grid, image and button rules. An unknown theme can still contain higher-specificity or !important overrides; use an iframe for strict style isolation. EMBED-EXAMPLE.txt explains this option. Disable duplicate theme/plugin floating contact buttons if desired.

CAROUSELS
Photos and reviews animate using CSS only. Hover or keyboard focus pauses motion. Checking Pause stops the animation and allows manual horizontal scrolling. Reduced-motion preferences disable autoplay. Duplicated carousel content is hidden from assistive technology.

BOOKING
Email: info@dovocci.com (opens email app; visitor sends message).
WhatsApp: +971502118501.
Review excerpts are a snapshot, not live Google synchronization.
Google Fonts is optional online typography; fallback fonts remain available.

VERIFICATION
HTML nesting, duplicate IDs, local asset references, script absence and ZIP integrity checked. All 78 local image/stylesheet dependencies returned HTTP 200.
Responsive browser checks at 320,390,700,768,1024,1366,1920 CSS pixels: no page-level horizontal overflow; correct service columns; readable heading colour.
Theme stress test: 143 image elements loaded (includes intentional loop duplicates), zero broken images; heading colours and grid survived generic conflicting rules.
CSS animation was running with nonzero transform; Pause switched animation off and enabled manual scroll.

Use integration-check.html only to inspect the generic-theme stress test; index.html is the actual website. No deployed external site was available to diagnose its server paths or theme-specific CSS.

SERVICE CATEGORY IMAGES UPDATE
All five specialist service cards now include images. Couple, Interior, Food and Corporate use your supplied reference photographs. Artwork uses an AI-generated illustrative image, labelled in its card. All are local assets and displayed without cropping.

REVIEW REFINEMENTS
Inquiry note typography and responsive footer-logo sizing corrected. All image tags have intrinsic width/height attributes. Artwork asset compressed to WebP. Carousel instructions explain reduced motion. Studio thumbnails intentionally open full photos in a new tab; no JavaScript switcher is used.

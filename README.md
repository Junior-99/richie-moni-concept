# Richie Moni Ventures — independent React concept

Six-page furniture website for a technology content series. Uncommissioned and unaffiliated. No real orders, payments, inventory or business notifications.

## Run

Node 22+: npm ci, npm run dev. Production: npm run build. Deploy the dist directory to GitHub Pages or Vercel. Vite uses relative asset paths and six HTML entrypoints, so direct page navigation works on static hosts.

## Pages and behaviour

- index.html: oversized charcoal/lime art direction, original Three.js cabinet rotating on scroll and drag, photographic product archive.
- collection.html: searchable genuine seller photographs with persistent shortlist.
- piece.html?item=media (or furniture/dining/office/gallery): item detail, enlarged photograph and shortlist controls.
- room.html: selected pieces, room, available wall width, finish, delivery area and notes; validated form saves on this device.
- studio.html: business context, practical measurement guide, public seller contact, source links and labelled generated room inspiration.
- dashboard.html: local brief counts, status editing, filtering, JSON downloads and optional concept-inbox submissions. Protected shared inbox supports authenticated status/notes editing, search, pagination and exports.

## Sources and images

Seller profile: https://fabamall.com/shops/richie-moni-ventures-153/ — explicitly displays “No Website”. Four historical listings plus one gallery photograph were observed on 22 October 2026. All five distinct furniture images are used. The source did not expose 20 images. Original seller watermarks remain; image rights remain with their owners and reuse permission is unestablished.

Product source URLs are retained in src/business.json. Public product-1.jpg, product-2.jpg, dining.jpg, office-chair.jpg and seller-gallery.jpg are genuine seller-published references. The original 3D model is illustrative, not a measured product model. public/hero.webp is generated room inspiration, labelled on the story page: contemporary oak/cream media cabinet and matching coffee table in a warm minimalist Accra apartment, olive wall and natural light. Source PNG: exec-e28518ed-1cbe-4de2-829f-17e49a062d5a.png, built-in imagegen. No paid generation API.

DESIGN.md records Pinterest, Webflow and Codrops inspiration. No purchased templates, copied template code or template imagery.

## Backend and handover

Supabase uses a publishable browser key. Private enquiry access is enforced by database membership and verified-email rules; anonymous visitors cannot read records. Only the approved creator account receives administrator membership after email verification. Registration alone does not grant access. The user must create their own password, verify email and sign in; that onboarding has not been completed by the agent.

Local drafts persist in localStorage on the current browser/device and can be exported. Optional shared submissions explicitly go to the creator’s demonstration inbox, not the real business. Do not enter personal/confidential information. No fabricated statistics or availability are shown.

Build and browser QA are recorded in the series document. Production use for the real business still requires its approval, media permissions, current catalogue/operating details, business onboarding, privacy/retention configuration and operational handover. This is a deployed concept with working workflows, not an official operational store.

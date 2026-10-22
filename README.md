# Sakinas BBQ Tuala website

A responsive, single-page restaurant website designed for mobile-first browsing.

## Included
- Responsive navigation and premium charcoal/gold visual styling
- Optimized remote food imagery, lazy-loaded menu/gallery images and a preloaded hero image
- Searchable menu and category filters
- Interactive order basket with quantity controls and a WhatsApp order enquiry
- Reservation/group enquiry form that opens a pre-filled WhatsApp message
- FAQ, Google Maps directions, reduced-motion support and accessibility labels
- Lightweight HTML/CSS/JavaScript with no framework build step

## Important launch checklist
This is a polished front-end website, not a connected restaurant POS or booking backend. Order and reservation actions open WhatsApp; staff must confirm them manually. There are no online payments, saved bookings, inventory, customer accounts or automated confirmations.

Before the site is treated as the restaurant's live service, the owner must confirm:
1. WhatsApp/phone number in `index.html` (currently `254733851928`).
2. Actual menu items, prices, descriptions and availability (the visible menu is demo content).
3. Address, map pin, opening hours, delivery/collection coverage and booking policies.
4. Replace stock photos with owner-approved restaurant and dish photography.
5. If automatic booking management or online payment is required, connect a secure backend and payment provider.

## Deployment
The site is a static website. Deploy the repository root on Vercel with no build command and the output directory set to the project root (or leave Vercel's static defaults).

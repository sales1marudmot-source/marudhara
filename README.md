# Marudhara Motors – Tata Dealership Website
React + Vite + Tailwind CSS + Lucide + React Router.

## Run locally
    npm install
    npm run dev      # http://localhost:5173
    npm run build    # production build in /dist

## Where to edit
- **Phone, WhatsApp (digits with country code, e.g. 919XXXXXXXXX), email, address, hours, map links, hero image, social links:** `src/data/siteConfig.js`. Empty values show placeholders and disable Call/WhatsApp buttons.
- **Vehicles (names, descriptions, images):** `src/data/vehicles.js`. Put licensed images in `public/images/` and set `image: '/images/nexon.jpg'`.
- **About copy:** `src/components/AboutSection.jsx`.
- **Enquiry form backend/CRM:** replace `submitEnquiry()` in `src/components/TestDriveForm.jsx`. Until then the form only shows a demo success message and sends nothing.
- **Colours:** `tailwind.config.js` (`brand`, `charcoal`).

Use only images you have rights to (e.g. from Tata Motors/dealer-provided materials).

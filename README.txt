CorbIQ ERP & CRM — Form Specification PWA

Purpose: private reference/specification build. No backend or real credentials are included.

Structure:
- index.html: module launcher and navigation
- css/style.css: shared UI styles based on supplied Material 3/Tailwind design
- js/app.js: shared navigation, forms, validation helpers
- manifest.json: PWA manifest
- sw.js: service worker
- modules/*.html: separate module/submodule pages
- assets/: placeholder CorbIQ logo, app icon and splash artwork

IMPORTANT:
This package is a front-end specification only. Credential/password fields are intentionally non-functional and should be encrypted/server-side in production.

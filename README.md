# Teshome Health Informatics Academy — Phase 1

Responsive React + Vite public academy website.

## Included
- Responsive homepage, navigation and mobile layout
- Searchable learning-area cards
- Learning tools section
- Link to existing Diabetes Probability Calculator
- About and contact sections

## Run locally
Requires Node.js 20 or newer.
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Production files are generated in `dist/`.

## Deploy on Render
1. Create a GitHub repository named `teshome-health-academy`.
2. Upload the contents of this folder (not the ZIP file itself).
3. In Render select **New + → Static Site** and connect the repository.
4. Build Command: `npm install && npm run build`
5. Publish Directory: `dist`
6. Deploy. Test the Render URL.
7. In Render → Settings → Custom Domains, add `teshome.com.et`.
8. Copy the exact DNS records Render displays into Ethiotelecom Plesk. Do not guess the target or delete unrelated DNS records.
9. Wait for domain verification and certificate issuance, then test https://teshome.com.et.

## Scope
This is Phase 1, the public-facing website. Student authentication, database, Moodle API integration, video storage and recording studio are later phases.

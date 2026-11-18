# DentaMehr — Dental Clinic UI Concept

A Persian (RTL) dental-clinic website concept built with **React, Vite, Tailwind CSS utilities and Lucide icons**. This is a front-end portfolio project, not a real clinic website or booking platform.

## Highlights

- Responsive RTL layout with Persian copy and Vazirmatn typography
- Service catalogue, sample team profiles, pricing table, FAQ and editorial cards
- Multi-step appointment flow with client-side validation
- Persian and Arabic numeral normalization for mobile numbers
- Mobile navigation, sticky booking action and accessible dialog semantics
- Reduced-motion support and intersection-based reveal transitions
- Page metadata, favicon, robots file and Vercel rewrite configuration

## Run locally

**Requirements:** Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Create and preview a production build:

```bash
npm run build
npm run preview
```

## Deploy

### Vercel

1. Push this project to a GitHub repository.
2. Import the repository in Vercel.
3. Keep the default Vite settings: build command `npm run build`, output directory `dist`.
4. Deploy. The included `vercel.json` keeps client-side routes working if routes are added later.

### Netlify

Use build command `npm run build` and publish directory `dist`.

## Project structure

```text
public/
  favicon.svg
  robots.txt
src/
  data/
    siteData.js       # editable demo content
  App.jsx             # page sections and interactive booking flow
  index.css           # responsive design system and component styles
  main.jsx            # React entry point
index.html             # Persian metadata and document shell
```

## Important demo limitations

- All clinic identity, staff names, phone/address details, prices, statistics, testimonials and treatment descriptions are fictional placeholders. Replace and clinically review all content before any real-world use.
- Booking and contact forms only update local UI state. No data is sent, stored, or transmitted; there is no API, database, SMS, email, calendar sync or payment integration.
- The displayed confirmation/reference code is generated in the browser and is not a real appointment confirmation.
- This project is not medical advice and must not be presented as a functioning healthcare service.

## Portfolio notes

Suggested case-study topics: RTL interface decisions, responsive layout strategy, form-state design, input normalization, accessibility, motion preferences, and deployment workflow.

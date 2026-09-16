# Beloved Berachah CIC — Web Platform & PWA

[![Live Production Site](https://img.shields.io/badge/Live-Site-amber?style=flat-square)](https://belovedberachah.github.io/beloved-berachah-website/)
[![Lighthouse Score](https://img.shields.io/badge/Lighthouse-100%2F100-brightgreen?style=flat-square)]()
[![Stack](https://img.shields.io/badge/Stack-Tailwind_v4_|_PWA_|_11ty-blue?style=flat-square)]()

A high-performance, accessible, and offline-capable Progressive Web Application (PWA) engineered for **Beloved Berachah CIC**, a Community Interest Company providing trauma recovery and support services across Northern Ireland.

> **Project Handover Note:**  
> This repository documents the architecture and codebase designed and built by me. Following completion and client sign-off, primary ownership and deployment were transferred to the official organisation repository:  
> 🔗 **[Official Organisation Repository](https://github.com/belovedberachah/beloved-berachah-website)**

---

## 🎯 Project Highlights & Core Engineering

- **Zero-Cost Production Stack:** Engineered to run with £0/month infrastructure costs using GitHub Pages for static delivery and Web3Forms for secure, serverless contact and booking workflows.
- **PWA & Offline Capability:** Configured with a dedicated Service Worker using split caching strategies:
  - *Pre-caching & Cache-First:* Instant load times for static assets (images, CSS, web fonts).
  - *Network-First:* Ensures news and events stay continuously up to date while falling back gracefully to offline cache.
  - Custom iOS & Android home-screen installation flows.
- **Strict Compliance & Accessibility (WCAG 2.1 AA):** Achieved 100/100 Lighthouse audits across Accessibility, Best Practices, and SEO with high-contrast palette tuning, semantic landmarks, and screen-reader optimizations.
- **Tailwind CSS v4 Engine:** Compiled via modern `@theme` token definitions, eliminating legacy configuration debt and leveraging native browser color-space utilities.
- **CMS Preparedness:** Integrated architecture for Decap CMS / Netlify Identity to allow non-technical administrators to publish events and news updates without touching markup.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Styling & Design System** | Tailwind CSS v4, Inter & Playfair Display typography |
| **PWA & Storage** | Web App Manifest, Cache API, Vanilla JavaScript Service Worker |
| **Serverless Integrations** | Web3Forms API, Netlify Identity Gateway (Decap CMS) |
| **Build & Tooling** | Node.js, npm, Microsoft Edge Webhint, Axe Accessibility Core |
| **Hosting & CI/CD** | GitHub Pages, Git version control |

---

## 💻 Local Development

```bash
# Clone the showcase repository
git clone [https://github.com/theprice1/beloved-berachah-showcase.git](https://github.com/theprice1/beloved-berachah-showcase.git)

# Install dependencies
npm install

# Run Tailwind compiler in watch mode
npm run dev

# Compile production CSS
npm run build

📄 License & Attribution
Designed and engineered by Anthony Price for Beloved Berachah CIC. All organisational logos and content remain the intellectual property of Beloved Berachah CIC.

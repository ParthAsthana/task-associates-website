# Task & Associates — Chartered Accountants

Marketing website for **Task & Associates**, a Lucknow-based chartered accountancy and
business consulting firm. It's a fast, fully responsive **static site** — plain HTML, CSS
and a little vanilla JavaScript, with **no build step and no dependencies**.

> 🌐 **Live site:** _add your deployed URL here after hosting_

---

## Pages

| Page | File |
|------|------|
| Home | `index.html` |
| About | `about.html` |
| Services | `services.html` |
| Industries | `industries.html` |
| Contact | `contact.html` |

## Highlights

- **CA India** branding with a "Connect with us on WhatsApp" top bar
- Service catalogue: **Statutory Audit, Income Tax, NRI Taxation (DTAA), GST, Bank Audit,
  Government & PSU Audit, Corporate Services**
- **"Our Presence" India map** — an inline SVG marking all 19 cities served, with Lucknow
  as the head office
- India-centric photography (Lucknow, RBI, Delhi Secretariat, BKC Mumbai, etc.)
- Fully responsive (desktop / tablet / mobile)

## Tech

- HTML5 + CSS3 (custom, variables-based design system) + vanilla JavaScript
- No frameworks, no bundler, no `node_modules` — just open the files

## Project structure

```
.
├── index.html          # Home
├── about.html          # About + leadership
├── services.html       # 7 service areas
├── industries.html     # Sectors + testimonials
├── contact.html        # 3 offices + enquiry form
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # Nav, mobile menu, scroll effects
└── images/             # Logo + photography
```

## Run locally

No build needed. From this folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

(or use any static server / just open `index.html` in a browser)

## Deploy (free)

This is a static site, so it works on any static host. Quick options:

- **Netlify** — drag-and-drop this folder, or connect this repo (publish dir = root).
- **Vercel** — import this repo (framework preset = "Other", output dir = root).
- **Hostinger** — upload the files to `public_html` via the File Manager.

Step-by-step instructions for each were shared separately.

## Image credits & licensing

> ⚠️ **Please review before going to production.**

- **Photographs** are sourced from **Wikimedia Commons** and are generally licensed under
  **CC BY / CC BY-SA**, which require **attribution**. For commercial production use, add the
  required credits, confirm each image's licence, or (recommended) replace them with your own
  photos of the office, team and city.
- The **CA India logo** is a trademark of the **Institute of Chartered Accountants of India
  (ICAI)** and must be used in line with ICAI's branding/usage guidelines (members only).

## Contact

**Task & Associates — Chartered Accountants**
14/40, Sector-14, Indira Nagar, Lucknow · Tel: 0522-4060660 · info@taskassociates.in

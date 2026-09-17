# Siyakhana Legal Advice Centre Website

A clean, responsive multi-page website for **Siyakhana Legal Advice Centre** — a community organisation providing free legal advice, human rights support, and social assistance to rural residents in the Alfred Nzo District (Mount Frere, Eastern Cape, South Africa).

---

## Project Overview

Siyakhana Legal Advice Centre was founded in 2024 by local activists and retired legal practitioners. The centre helps vulnerable community members (including the elderly, women, children, people with disabilities, and the rural poor) with:

- Free legal advice and consultation
- SASSA grant applications and social services support
- Community dispute resolution
- Human rights awareness and education
- Partnerships with traditional leaders and local government

---

## Pages

| Page         | File                     | Description                                      |
|--------------|--------------------------|--------------------------------------------------|
| Home         | `index.html`             | Welcome page with organisation introduction      |
| About        | `Pages/about.html`       | History, Mission & Vision                        |
| Services     | `Pages/services.html`    | Overview of services offered                     |
| Enquiry      | `Pages/enquiry.html`     | Enquiry / consultation booking form              |
| Contact Us   | `Pages/contactus.html`   | Contact details, map, and contact form           |

---

## Folder Structure

```
Siyakhana-Website/
│
├── index.html
├── README.md
│
├── Pages/
│   ├── about.html
│   ├── services.html
│   ├── enquiry.html
│   └── contactus.html
│
├── Css/
│   └── style.css
│
└── Images/
    ├── Organization logo.png
    ├── legal-advice-concept-color-illustration-vector.jpg
    ├── Home page picture.jpg
    ├── Legal Aid.jpg
    ├── Community.jpg
    └── Donor funding.jpg
```

> **Important:** Place your image files inside the `Images/` folder using the exact names above (or update the `src` paths in the HTML).

---

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, CSS Variables, Media Queries)
- Font Awesome 6 (via CDN)
- Google Maps Embed

---

## How to Run Locally

1. Download the project folder.
2. Make sure all your images are inside the `Images/` folder.
3. Open `index.html` in a modern browser (Chrome, Firefox, Edge, or Safari).

Or use a local server:

```bash
python -m http.server 8000
```

Then visit: `http://localhost:8000`

---

## Features

- Clean, consistent header and navigation on every page
- Fully responsive design (mobile, tablet, desktop)
- Service cards with hover effects
- Enquiry form with personal details and booking options
- Contact page with address, opening hours, Google Map, and message form
- Professional footer with contact details and social icons
- Fixed “Chat with Siyakhana Legal” button

---

## Notes

- Forms currently use `action="#"` (they do not submit data yet).  
  To make them functional, connect them to a service such as Formspree, Netlify Forms, or your own backend.
- Social media links are placeholders — replace them with your real profile URLs.
- The Google Map embed points to Mount Frere Paralegal Advice Centre. Update the `src` if needed.

---

## Contact Information

- **Helpline:** 0800 110 110 (Mon–Fri 09:00–17:00)
- **Direct Line:** 041 818 5643
- **Email:** info@siyakhanalegal.co.za
- **Fraud & Ethics Hotline:** 0800 153 728
- **Physical Address:** Siyakhana Head Office, Mount Frere, Eastern Cape, South Africa
- **Postal Address:** P.O. Box 543, Mount Frere, Eastern Cape, 2000, South Africa

---

**© 2026 Siyakhana Legal Advice Centre. All rights reserved.**

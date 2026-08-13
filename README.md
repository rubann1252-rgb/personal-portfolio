https://personal-portfolio-pi-woad-95.vercel.app/


# Ruban N — Developer Portfolio
 
A single-page personal portfolio for **Ruban N**, a Computer Science & Engineering student and full-stack developer intern, built to showcase his skills, experience, and certifications to recruiters.
 
**🔗 Live site:** https://personal-portfolio-pi-woad-95.vercel.app/
 
---
 
## About This Project
 
This is a self-contained, single-file portfolio site — no build tools, no frameworks, no dependencies to install. Just one `index.html` file with everything (HTML, CSS, JS, and even the profile photo) embedded inside it, so it deploys anywhere with zero configuration.
 
## Sections
 
- **Hero** — Introduction and tagline: *"CSE Student. Full-Stack Intern. Cloud-Curious Developer."*
- **About Me** — Background, education, and current focus
- **Skills** — Programming languages, web development, and cloud/networking skills
- **Experience** — Full-Stack Development internship at Viruzverse Solution, presented as a case study (Problem / Role / Solution / Outcome)
- **Certification & Education** — Cloud Computing & Computer Networking certifications, plus full academic timeline
- **Contact** — Direct contact details and a working contact form
## Tech Stack
 
- **HTML5, CSS3, vanilla JavaScript** — no frameworks or build step required
- **Google Fonts** — Space Grotesk (headings) + Inter (body)
- **[Formspree](https://formspree.io)** — powers the contact form, so messages land directly in the inbox without needing a backend server
## Features
 
- Fully responsive (mobile, tablet, desktop)
- Smooth-scroll navigation with active-section highlighting
- Scroll-triggered fade-in animations
- Working contact form with inline success/error states
- `mailto:` fallback link for direct email
- Respects `prefers-reduced-motion` for accessibility
- Profile photo embedded as base64 — no external image file needed
## Deployment
 
This project is deployed on **Vercel**, connected to this GitHub repository.
 
### To deploy your own copy:
 
1. Fork or clone this repository
2. Push it to your own GitHub account
3. Go to [vercel.com](https://vercel.com) → **New Project** → import this repository
4. Vercel will auto-detect it as a static site — no build settings needed
5. Click **Deploy**
**Important:** the entry file must be named exactly `index.html` at the root of the repo, or the deployment will return a 404 at the root URL.
 
### Connecting the contact form
 
The contact form uses Formspree to deliver messages. Before it will work:
 
1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form and set the delivery email to your own inbox
3. Copy your unique form endpoint (e.g. `https://formspree.io/f/xxxxxxx`)
4. In `index.html`, find this line:
```html
   <form id="contactForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
```
5. Replace `YOUR_FORM_ID`'s full URL with your own endpoint
6. Commit and push — Vercel will redeploy automatically
## Local Preview
 
No installation needed — just open `index.html` directly in a browser, or use a simple local server:
 
```bash
# Python
python3 -m http.server 8000
 
# Node
npx serve
```
 
## Contact
 
- **Email:** rubann1252@gmail.com
- **Phone:** +91 63852 84761
- **LinkedIn:** [linkedin.com/in/ruban-undefined-56a6722b5](https://linkedin.com/in/ruban-undefined-56a6722b5)
- **Location:** Coimbatore, Tamil Nadu, India
---
 
Built with care and clean code.
 

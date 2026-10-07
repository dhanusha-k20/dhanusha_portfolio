# Dhanusha K — Portfolio

🔗 **Live site:** https://dhanusha-k20.github.io/dhanusha_portfolio/

A personal portfolio website for Dhanusha K, a penetration tester based in Kozhikode, Kerala — built with a Kali Linux inspired visual theme (swapped to red instead of the signature blue).

## About

A single-page, scroll-linked experience covering Home, About, Explore, and Contact, plus standalone directory-style pages for blogs, walkthroughs, certifications, credentials, and tools built — styled to feel like navigating a terminal/file system.

## Features

- Scroll-driven section handoffs with eased transitions (Home → About → Explore → Contact)
- Terminal-style typing animation on the About section, skippable via click / Enter / Space
- Kali/Thunar-inspired directory grid for Explore, linking out to themed sub-pages
- 3D-tilt file tiles with a PDF/image lightbox viewer for certifications, walkthroughs, and credentials
- Medium-style long-form layout for blog articles
- Animated count-up stats and a two-screen scroll layout on the Credentials page
- Tool showcase cards linking out to GitHub repos, with independent documentation links
- Fully responsive, dark theme only

## Tech Stack

Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step.

## Structure

```
├── index.html              # Home / About / Explore / Contact (single page)
├── style.css               # Shared stylesheet
├── blogs.html              # Blog directory listing
├── blogs/                  # Individual blog article pages
├── walkthroughs.html       # CTF / lab walkthrough listing
├── walkthroughs/           # Individual writeup documents
├── certifications.html     # Certification file listing
├── certs/                  # Individual certification PDFs
├── credentials.html        # Stats + profile (degree, sectors, tools)
├── creds/                  # Individual credential documents
├── tools_built.html        # Tools built, linking to their GitHub repos
└── tools/                  # Tool logos and documentation files
```

## Run Locally

Clone the repo and open `index.html` in a browser, or serve it with any static server (e.g. the VS Code Live Server extension).

## Contact

- [LinkedIn](https://www.linkedin.com/in/dhanusha-pentester/)
- [GitHub](https://github.com/dhanusha-k20)
- [TryHackMe](https://tryhackme.com/p/dhanusha)

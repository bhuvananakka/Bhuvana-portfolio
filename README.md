# 🌟 Bhuvana Nakka — Personal Portfolio Website

A fully self-contained, single-file personal portfolio website for **Sri Satya Bhuvaneswari Devi Nakka (Bhuvana Nakka)**, a B.Tech Computer Science & Engineering student at Aditya College of Engineering and Technology (ACET), Andhra Pradesh.

---

## 👤 About the Owner

| Field | Details |
|---|---|
| **Full Name** | Sri Satya Bhuvaneswari Devi Nakka |
| **Known As** | Bhuvana Nakka |
| **Degree** | B.Tech in Computer Science & Engineering |
| **College** | Aditya College of Engineering and Technology (ACET) |
| **Year** | 2nd Year (2024–2028) |
| **Email** | bhuvananakka93@gmail.com |
| **LinkedIn** | [bhuvaneswari-devi-nakka](https://www.linkedin.com/in/bhuvaneswari-devi-nakka-97986935b/) |
| **Location** | Andhra Pradesh, India |

---

## 📁 File Structure

Everything lives in a **single HTML file** — no frameworks, no build tools, no external dependencies (except Google Fonts loaded via CDN).

```
bhuvana_portfolio.html
├── <style>          — All CSS (tokens, layout, animations, responsive)
├── <nav>            — Fixed top navigation with pill-style module links
├── #home            — Hero section with profile photo + info card
├── #about           — Bio, stats grid, personal quote
├── #education       — Academic timeline (SSC → Intermediate → B.Tech)
├── #skills          — Skill cards with animated progress bars
├── #achievements    — Milestone & recognition cards
├── #projects        — Project showcase cards with links
├── #experience      — Experience & coursework cards
├── #contact         — Contact links + message form
├── <footer>         — Credit line
└── <script>         — Navigation, scroll spy, skill bar animations
```

---

## 🗂️ Sections & Modules

### 🏠 Home
- Full name display with elegant serif typography
- Circular profile photo with spinning gold rings
- Hover effect: gold glow, zoom-in, enhanced sharpness
- Info card: degree, college, location, open-to status
- Two CTA buttons: **Get in Touch** → Contact | **View Projects** → Projects

### 👩‍💻 About
- Personal bio paragraph
- Stats grid: Year · Skills count · Projects Built · Branch
- Inspirational personal quote block

### 🎓 Education
- Vertical timeline layout with gold dot markers
- **SSC** — Likhitha High School, Chandramampalli, AP (up to 2022)
- **Intermediate (MPC)** — KSN Junior College, Samarlakota, AP (2022–2024)
- **B.Tech CSE** — ACET, Surampalem, AP (2024–2028)

### 🛠️ Skills
Ten skill cards with animated progress bars, each reflecting strong proficiency:

| Skill | Level |
|---|---|
| C Programming | 88% |
| Java | 82% |
| Python | 86% |
| HTML Basics | 83% |
| Data Structures | 90% |
| Problem Solving | 88% |
| Debugging | 85% |
| AI / ML Project Exploration | 87% |
| Teamwork & Communication | 95% |
| Adaptability & Continuous Learning | 93% |

Bars animate into view when scrolled into the viewport.

### 🏆 Achievements
Five recognition cards covering:
- AI/ML Project Contributor
- Programming Proficiency (C & Java)
- Data Structures Mastery
- Strong Communication Skills
- Active Learner & Team Contributor

### 🚀 Projects
Two detailed project cards, each with tech tags:

| Project | Type | Link |
|---|---|---|
| **Sign Language Translator** | AI/ML · Computer Vision · Assistive Tech | Embedded — opens in new tab |
| **Campus Connect** | Web Development · College Platform | — |

The Sign Language Translator card includes a **"View Project →"** button that opens the full working app (embedded as a data URI — no hosting required).

### 💼 Experiences
Four experience cards covering:
- AI/ML Assistive Technology Project
- Data Structures & Algorithms Practice
- Web Development Exploration
- Academic Coursework & Labs

### 📬 Contact
- Clickable email link
- Clickable LinkedIn profile link
- Location display
- Message form (Name, Email, Subject, Message) — UI ready, connects to email on send

---

## ✨ Design System

### Color Palette
| Token | Value | Usage |
|---|---|---|
| `--ink` | `#1a1a2e` | Primary text |
| `--ink2` | `#3a3a5c` | Secondary text |
| `--ink3` | `#7a7a9a` | Muted labels |
| `--parchment` | `#f7f5f0` | Page background |
| `--gold` | `#b5883e` | Accent / highlights |
| `--gold-lt` | `#d4a85a` | Hover gold |
| `--white` | `#ffffff` | Card backgrounds |

### Typography
| Role | Font |
|---|---|
| Headings | Cormorant Garamond (serif) |
| Body / UI | DM Sans |
| Labels / Code / Mono | DM Mono |

### Key Interactions
- **Profile photo** — gold glow ring + zoom + sharpness boost on hover
- **Skill bars** — animate from 0 on scroll into view
- **Project cards** — lift + gold underline sweep on hover
- **Nav pills** — active section highlighted in filled gold as you scroll
- **Contact links** — slide right with gold border on hover

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Structure | Pure HTML5 |
| Styling | Vanilla CSS3 (custom properties, grid, flexbox, keyframes) |
| Interactivity | Vanilla JavaScript |
| Fonts | Google Fonts CDN (Cormorant Garamond, DM Sans, DM Mono) |
| Profile photo | Embedded as Base64 data URI |
| Project demo | Embedded as Base64 data URI (silentVoice.html) |
| Build tool | None — single file, zero dependencies |

---

## 📱 Responsiveness

| Breakpoint | Behaviour |
|---|---|
| Desktop (> 1050px) | Full two-column hero, pill nav visible |
| Tablet / Mobile (≤ 1050px) | Single-column layout, hamburger menu, stacked grids |

---

## 🚀 How to Use

1. **Download** `bhuvana_portfolio.html`
2. **Open** in any modern browser (Chrome, Edge, Firefox, Safari)
3. No server, no installation, no internet required — it works completely offline

### To customise:
- **Update bio or details** — edit the relevant HTML section directly
- **Replace profile photo** — swap the Base64 `src` in the `.profile-avatar img` tag with a new Base64-encoded image
- **Add a new project** — copy a `.proj-card` div inside `#projects` and fill in your details
- **Add a skill** — copy a `.skill-card` div inside `#skills` and set the bar width percentage
- **Link Campus Connect** — add an `<a href="..." class="proj-link-btn">` inside the Campus Connect `.proj-card`

---

## 📌 Notes

- The **contact form** is UI-only and does not submit to a backend. To enable it, integrate a service like [Formspree](https://formspree.io) or [EmailJS](https://www.emailjs.com).
- The **profile photo and Silent Voice app** are fully embedded as Base64 — the file is self-contained and sharable without any external assets.
- The portfolio is **ad-free** and contains no tracking scripts.

---

## 📄 License

Personal portfolio — all content belongs to Sri Satya Bhuvaneswari Devi Nakka. Not for redistribution.

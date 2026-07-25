# Portfolio
DevOps &amp; database engineering portfolio — projects, skills, and experience.

## License
Code is MIT licensed — feel free to use the structure/design for your own portfolio.
Personal content (photo, bio, project descriptions) is not licensed for reuse.

# Syed Muhammad Umayr — Portfolio

Personal portfolio site showcasing my work in **DevOps and database engineering**, alongside game development. Built as a static site, no frameworks, no build step — just HTML, CSS, and vanilla JavaScript.

**Live site:** [your GitHub Pages URL here]

---

## About This Project

I'm a final-year Software Engineering student at NUML Faisalabad, currently a remote DevOps Intern at CodeAlpha working on CI/CD pipelines, Docker, and AWS. This portfolio pulls together my DevOps/database work and my earlier game development background (Godot 4) into one site.

The design is built around a CI/CD pipeline metaphor, since that's the world I work in day to day:

- The navigation bar is styled like a running pipeline — each stage "completes" and lights up as you scroll past its section
- Projects are grouped into two parallel tracks (`devops-track` / `gamedev-track`), mirroring a GitHub Actions build matrix
- Project and skill status badges (`✓ shipped`, `◌ in progress`) reflect real, current status rather than generic labels

## Sections

| Section | What it covers |
|---|---|
| **Hero** | Name, tagline, short intro, profile photo |
| **About** | Background, education, current focus |
| **Experience** | Timeline — CodeAlpha internship, Gaming Doctrine internship, NUML education |
| **Projects** | Dockerized Task API, Java CI/CD pipeline, CodeAlpha web server deployment, Ranikot Chronicles (Godot 4 FYP) |
| **Skills** | Split into **core** (used in shipped work) and **currently learning** (Kubernetes/KCNA, AWS) — kept honest on purpose |
| **Contact** | Email, GitHub, LinkedIn |

## Features

- Scroll progress bar (top of page) that fills as you read
- Pipeline-style nav that tracks and highlights your current section
- Scroll-triggered reveal animations across every section, staggered per element
- Hover interactions on project cards, skill chips, and links
- Fully responsive — stacks cleanly down to mobile
- Respects `prefers-reduced-motion` for accessibility

## Tech Stack

- **HTML5 / CSS3** — no CSS framework, custom design system via CSS variables
- **Vanilla JavaScript** — `IntersectionObserver` for scroll effects, no dependencies
- **Fonts** — [JetBrains Mono](https://www.jetbrains.com/lp/mono/) (headings/labels) + [Inter](https://rsms.me/inter/) (body text), via Google Fonts
- **Hosting** — GitHub Pages

## Project Structure

```
.
├── index.html        # Page markup and structure
├── styles.css         # All styling (design tokens, layout, animations)
├── umayr-photo.jpg    # Profile photo
└── README.md
```

## Running Locally

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# then either:
open index.html                  # macOS — opens directly in your default browser
# or
python -m http.server 3000       # serve it, then visit http://localhost:3000
```

## Deployment

Hosted via **GitHub Pages**, deployed from the `main` branch (`/root`). Any push to `main` updates the live site automatically within a minute or so.

## Customization

The color palette, fonts, and spacing are all defined as CSS custom properties at the top of `styles.css` (`:root`), so the whole visual identity can be adjusted from one place. Section content lives directly in `index.html`.

## License

Code is MIT licensed — feel free to use the structure/design as a starting point for your own portfolio.
Personal content (photo, bio, and project descriptions) is not licensed for reuse.

## Contact

- Email: umair786346@gmail.com
- GitHub: [github.com/syed-m-umair](https://github.com/syed-m-umair)
- LinkedIn: [linkedin.com/in/syed-muhammad-umair-1559a3318](linkedin.com/in/syed-muhammad-umair-1559a3318)

# Praveen Raj Thulasi S — Portfolio

**Live site:** https://praveen-raj-thulasi.github.io/Portfolio/

A personal portfolio website for Praveen Raj Thulasi S, Full Stack Developer, AI Engineer and Cloud Computing Engineer. It shows an animated hero, a flower intro, selected projects, a "My Journey" timeline, services, a tech-stack marquee, a contact section and a resume page.

Pages:

- Portfolio: https://praveen-raj-thulasi.github.io/Portfolio/
- Resume: https://praveen-raj-thulasi.github.io/Portfolio/resume.html

## Run it locally

The site is plain HTML, CSS and JavaScript with no build step.

Option 1: open `index.html` directly in a browser.

Option 2 (recommended, so file paths behave as they do on the web):

```bash
python3 -m http.server 8000
```

Then open:

- Portfolio: http://localhost:8000/index.html
- Resume: http://localhost:8000/resume.html

## Deployment

The site is hosted with GitHub Pages from the `main` branch, root folder. The `.nojekyll` file turns off Jekyll, so the files are served exactly as written. Each push to `main` rebuilds the site, usually within a minute or two.

## Pages

| File | What it is |
| --- | --- |
| `index.html` | Main portfolio page: hero, flower intro, selected projects, journey timeline, services, tech marquee, contact |
| `resume.html` | Resume (curriculum vitae) page, linked from the RESUME card in the flower intro |

## File layout

```
.
├── index.html                  Main portfolio page
├── resume.html                 Resume page
├── README.md
├── .gitignore
├── .nojekyll                   Turns off Jekyll for GitHub Pages
├── assets/
│   ├── favicon.svg             Browser tab icon (PRT)
│   ├── favicon.png             PNG favicon
│   ├── apple-touch-icon.png    Home-screen icon
│   ├── og-image.png            Social share image
│   ├── profile-sharp.png       Square profile photo shown in the flower centre
│   ├── Profile (copy 1).png    High-resolution source photo (for re-processing)
│   ├── aws.svg                 AWS badge for the tech marquee (placeholder artwork)
│   └── tech-icons/             Icons for the tech-stack marquee
├── Project Images/
│   ├── originals/              Project screenshots and experience images
│   ├── cartoon-face.jpg        Image in the contact section
│   └── grid-waves-bg.jpg       Background for the services section
└── Gsap X Webflow_files/       GSAP, ScrollTrigger, Lenis and other scripts, fonts and images used by the page
```

## Customising

- **Name, bio and contact links:** edit the hero, footer, contact cards and the clipboard copy text in `index.html`. Search for your name and email.
- **Projects:** the three project cards in "Selected Projects" link to GitHub repositories and use the screenshots in `Project Images/originals/`.
- **Journey timeline:** each milestone is a `div.j-milestone` with an `id`. Positions are set with `left` and `top` percentages. The reveal order is the `milestones` array in the journey script.
- **Tech marquee:** icons are in `assets/tech-icons/`. Each row repeats the same set of labels.
- **Profile photo:** replace `assets/profile-sharp.png`, or change the `href` on the `<image>` element in the flower section.
- **Resume:** edit `resume.html` directly.

## Credits and licensing

- The layout, animations and some styling are based on the "Learn GSAP" Webflow template by OFF+BRAND. Confirm the template's licence terms before redistributing this repository publicly.
- Animations use [GSAP](https://gsap.com) with ScrollTrigger, SplitText and other GSAP plugins.
- Smooth scrolling uses [Lenis](https://github.com/darkroomengineering/lenis).
- Fonts: Anton and Work Sans.
- Tech-stack icons are third-party logos, used for identification only.
- The AWS badge (`assets/tech-icons/aws.svg`) is placeholder artwork, not the official AWS logo.

## Contact

- Email: praveenrajthulasioff@gmail.com
- LinkedIn: https://www.linkedin.com/in/praveen-raj-thulasi-s/
- GitHub: https://github.com/Praveen-Raj-Thulasi

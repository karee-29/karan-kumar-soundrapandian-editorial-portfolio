# Karan Kumar Soundrapandian — Editorial Portfolio

A responsive, single-page portfolio for an Electronics and Computer Engineering student, software builder, analytics enthusiast, photographer and filmmaker. The visual direction uses an editorial magazine aesthetic: warm ivory, cobalt, acid lime, orange, lavender, oversized typography, geometric SVG/CSS illustrations and an asymmetric portrait layout.

## Included
- Complete portfolio: hero, about, selected projects, experience/leadership, achievements, skills, creative practice, education/certifications, contact and footer
- Responsive sticky navigation with active-section state and mobile menu
- Actual supplied portrait at `public/assets/portrait.jpg`
- Actual supplied resume at `public/assets/resume.pdf`, wired to both download buttons
- CSS/SVG-style diagrams for the project cards
- Working email, phone, LinkedIn, GitHub, section navigation and resume links
- Reduced-motion support, focus styles, alt text and semantic landmarks

## Run locally

Requires Node.js 20+.

```bash
npm install
npm run dev
```

Build for deployment:

```bash
npm run build
npm run preview
```

The static production output is generated in `dist/`. It can be deployed to Vercel, Netlify, GitHub Pages (with suitable base-path configuration), or another static hosting provider.

## Factual notes
- Project descriptions are based on the supplied resume and project context. Individual repository URLs were not supplied for every project, so the project cards intentionally do not invent repository links. The GitHub CTA points to the real profile: https://github.com/karee-29.
- The IFP Top 25 nomination is treated as an achievement, not a conventional certification.
- The credential list includes the five conventional credentials named in the resume; the IFP nomination is presented separately.
- The Creative section uses the supplied portrait as a single genuine photo. Abstract shapes are decorative and are not represented as photography work samples.
- Do not claim an individual project is deployed or feature-complete beyond its actual implementation.

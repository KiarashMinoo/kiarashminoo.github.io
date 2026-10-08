# kiarashminoo.com

Source for my personal portfolio at [kiarashminoo.com](https://kiarashminoo.com).

The site is a small static GitHub Pages project. It contains my current engineering profile, selected projects, work history, technical writing links, contact details, and the downloadable CV used from the site header.

[![Architecture diagram](https://gitdiagram.com/diagram-badge.svg)](https://gitdiagram.com/kiarashminoo/kiarashminoo.github.io?utm_source=readme&utm_medium=badge)

## Main content

The project section currently highlights:

- ThunderPropagator and its public .NET 8/9/10 modules
- IIIF.Manifest.Serializer.Net and related .NET 10 proof-of-concept repositories
- MinooTrading platform work at a high level

The downloadable CV is stored at:

```text
assets/Ahmad-Kiarash-Minoo-CV.pdf
```

## Local files

```text
index.html       Main page content and structured metadata
styles.css       Site styling and responsive layout
script.js        Navigation and small client-side behaviours
assets/          Images, project marks and the downloadable CV
CNAME            Custom-domain configuration
```

## GitHub Pages

The site is published from the `main` branch using GitHub Pages. The custom domain is configured through `CNAME` as:

```text
kiarashminoo.com
```

When the CV changes, replace `assets/Ahmad-Kiarash-Minoo-CV.pdf` so the website download stays in sync with the current resume.

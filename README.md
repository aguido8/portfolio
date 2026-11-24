# Alexander Guido — Engineering Portfolio

A static, dependency-free engineering portfolio for GitHub Pages. The production site is [aguido8.github.io/portfolio/](https://aguido8.github.io/portfolio/). The engineering rebuild is intended for review before merging into main.

## Preview locally

From the repository root:

    python3 -m http.server 8000

Open http://localhost:8000/ in a browser. No package installation, build step or backend is required. All internal paths are relative so the site also works below /portfolio/ on GitHub Pages.

## Structure

- index.html — recruiter-friendly homepage and selected work
- projects.html — case-study directory
- trinity.html — telescope CAD, structural simulation, Monte Carlo/optics, FEA, prototypes and operations
- racing-clubs.html — Off-Road suspension, shock reducer, joint sizing and FEA
- me2110.html — autonomous robot requirements, mechanical integration, manufacturing, programming and failures
- wind-turbine.html — prototype, preliminary CFD, measurements and paper
- gsu.html — particle detection and computational research
- experience.html, aviation.html, frc.html, peer-instructor.html, theta-chi.html — experience and affiliations
- about.html, resume.html, contact.html — education, skills, printable résumé and contact
- styles.css — shared responsive design system
- assets/ — original images preserved; additional evidence slots listed in PORTFOLIO_REVIEW.md

All case studies use ordinary static HTML. To add a figure, replace its documentation-slot figure with the example markup in PORTFOLIO_REVIEW.md. The placeholders intentionally make no external image requests.

## Editorial principles

Use the November 2026 résumé for role names, dates and verified results. Distinguish measured results from design targets, illustrative diagrams from released CAD, and ongoing analysis from validated performance. Do not upload proprietary team files or unpublished research without approval. See the review checklist for evidence gaps and image replacements.

## Deployment

Review the draft pull request and preview the branch locally. Merge to main only when the content and assets are approved. No deployment settings or workflows are changed by this redesign.

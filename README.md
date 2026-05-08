# noman024.github.io Portfolio

Dual-track personal site for:
- **Industry audience** (recruiters, hiring managers, startup teams)
- **Academic audience** (faculty, PhD admissions committees, research collaborators)

## Site Strategy
- Single domain with two clear identity modes:
  - **Industry Track**: deployment impact, production systems, measurable engineering outcomes
  - **Academic Track**: research direction, publications, methodology, reproducibility intent
- Shared factual foundation (education, publications, projects) with audience-specific framing.

## Current Structure
- `index.html`: main content, dual-mode gateway, shared experience and project sections
- `css/style.css`: visual system and responsive layout
- `images/`: visual assets (profile and media)

## Content Maintenance Rules
1. Keep claims evidence-backed (metrics, publications, links).
2. Use **industry language** only in industry sections (throughput, latency, cost, reliability).
3. Use **academic language** only in academic sections (problem framing, method, evaluation rigor).
4. Avoid mixed messaging in hero/intro blocks.
5. Update publication entries in one pass (title, venue, DOI, author order).

## Recommended Next Additions
- Dedicated pages:
  - `/industry.html`
  - `/academic.html`
- Downloadable documents:
  - `Resume-Industry.pdf`
  - `CV-Academic.pdf`

## CV PDF Automation
- Workflow: `.github/workflows/build-cv-pdfs.yml` in the `noman024` profile repo.
- Trigger: on push when `CV-Industry.tex` or `CV-Academic.tex` changes, or via manual dispatch.
- Output: regenerates `CV-Industry.pdf` and `CV-Academic.pdf` and commits them automatically.
- Research statement page with faculty-fit map.

## Local Editing
Edit `index.html` and `css/style.css`, then open `index.html` in a browser to validate rendering and navigation anchors.

## Contact
mutasim.billah024@gmail.com

# Consulate Diff Watch (Manual) – Monthly Changelog (B2B)

**Live Site:** [https://chaos-factory.github.io/ideator-execution-008Digitalnomadvisa-5-ConsulateDiffWatchManualMonthlychangelogB2B/](https://chaos-factory.github.io/ideator-execution-008Digitalnomadvisa-5-ConsulateDiffWatchManualMonthlychangelogB2B/)

Static, editor‑curated feed delivering a monthly, source‑linked changelog of official consulate/program page updates for agencies/consultants. Includes /diffs/YYYY‑MM index, diff detail excerpts, RSS and CSV; schema‑validated snapshots.jsonl workflow.

## Overview

Consulate Diff Watch provides immigration professionals with curated, reliable intelligence on consulate and visa program changes. Our editorial team manually verifies every change to ensure quality and relevance.

## Features

- 📅 **Monthly Digests**: Consolidated reports delivered mid-month
- ✅ **Editor-Curated**: Manual verification by immigration experts
- 📊 **Source-Linked Diffs**: Before/after excerpts with official source links
- 🔔 **Multiple Formats**: Web, RSS feed, and CSV exports
- 🔒 **Schema-Validated**: Structured data for easy integration

## Site Structure

- `/` - Landing page with features, pricing, and CTAs
- `/diffs/2025-12/` - Sample monthly changelog with 3 diff cards
- `/about/` - Editorial process and company information
- `/feeds/rss.xml` - RSS feed for automated updates

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch. Pull requests create preview deployments for review.

### Workflows

- **Deploy to GitHub Pages** (`.github/workflows/deploy.yml`): Automatic deployment on push to main
- **Deploy PR Preview** (`.github/workflows/preview.yml`): Preview deployments for pull requests

## Local Development

To view the site locally:

```bash
# Clone the repository
git clone https://github.com/chaos-factory/ideator-execution-008Digitalnomadvisa-5-ConsulateDiffWatchManualMonthlychangelogB2B.git
cd ideator-execution-008Digitalnomadvisa-5-ConsulateDiffWatchManualMonthlychangelogB2B

# Open in browser (no build step required)
open index.html
# or use a simple HTTP server
python -m http.server 8000
# Then visit http://localhost:8000
```

## Tech Stack

- **Frontend**: HTML5, CSS3 (custom styling, no frameworks)
- **Deployment**: GitHub Pages (via GitHub Actions)
- **Preview**: Surge.sh for PR previews (fallback to instructions)

## License

All rights reserved © 2025 Consulate Diff Watch
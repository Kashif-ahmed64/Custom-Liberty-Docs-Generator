# Liberty Invigilator Pass Generator

Web tool for generating printable invigilator lanyard passes for the **Trade Apprentice Test** at Liberty Daharki Powers Limited.

## Features

- Editable invigilator name and test date
- Liberty logo (with custom logo upload)
- 6 theme templates (Liberty Red, Deep Maroon, Navy, Forest Green, Classic Black, White Minimal)
- Print-ready output (white theme, ink-friendly)
- Download as PNG (print-ready or themed)
- Standard lanyard pass size: **90mm × 140mm**

## Usage

1. Open the site
2. Enter the invigilator name
3. Confirm the test date (default: 17 June 2026)
4. Optionally pick a theme or upload a custom logo
5. Click **Print Pass** or **Download PNG**

> **Note:** Print and "Print Ready" download automatically switch to a white theme. The logo remains visible.

## Deploy on Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import the GitHub repository
4. Deploy (no build step required — static HTML)

## Local Preview

Open `index.html` in a browser, or run:

```bash
npx serve .
```

# Liberty Pass Generator

Reusable web tool for generating printable lanyard passes for **Liberty Daharki Powers Limited** events (Invigilator, Trade Apprentice Test, and more).

## Features

- **All fields live-editable** — text updates on the card as you type
- **Default Invigilator template** — logo, company name, role tag, name, date
- **Add custom blocks** — Text Field, Logo Field, or Tag Box (multi-line badge)
- **Formatting per field** — size, weight, color, alignment, uppercase, letter spacing, optional label
- **Reorder & remove** fields with ↑ ↓ ✕ controls
- **6 theme templates** + custom logo upload per logo field
- **Print-ready white output** — logo stays visible
- **Download PNG** (print-ready or themed)
- **Standard size:** 90mm × 140mm

## Default Template

| Zone | Content |
|------|---------|
| Header | Liberty logo + Liberty Daharki Powers Limited |
| Body | INVIGILATOR / Trade Apprentice Test tag + Name |
| Footer | Test Date + 17 June 2026 |

Change any text for other events. Use **Reset Template** to restore defaults.

## Deploy on Vercel

1. Import `Kashif-ahmed64/liberty-invigilator-pass` on [vercel.com](https://vercel.com)
2. Deploy (static site, no build step)

## Local Preview

```bash
npx serve .
```

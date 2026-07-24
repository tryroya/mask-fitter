# MaskFitter — marketing site

Landing site for MaskFitter (consumer CPAP-mask fit tool by Orma Sleep). Deployed via GitHub Pages
(`tryroya/mask-fitter` → https://tryroya.github.io/mask-fitter/). The live product demo it links to is
separate: https://maskfitter.pages.dev (Cloudflare Pages, owner/builder Hamed Malek, Stripe test mode).

- **Built 2026-07-23 (Adrian directive):** ormasleep.com format; hero = CSS iPhone mockup auto-cycling
  **3 app-feature slides** (fit scan → best matches → your size) + ambient animated rings/glows;
  Instagram-style brand cards beside sections ("Every face is different." / "Fit, not diagnosis. Ever.").
  `prefers-reduced-motion` disables all animation and the slideshow.
- **Claims posture — F9 ruling applies:** MaskFitter is ruled 🟢 NOT-A-DEVICE *conditional on the framing
  rules* in `brain/regulatory/rulings/maskfitter-framing-rules.md`. Copy on this site is fit/comfort/
  product-matching ONLY: no screening/risk/detection, no disease naming, no SpO2/AHI, no "medical-grade",
  no accuracy percentages (accuracy validation is a pending board go/no-go). The phone mockup shows fit
  labels ("Great fit"), never health output. Do not add any of these.
- The weekly `orma-samd-gate` / `orma-website` sweeps should include this page (it's a public label surface).
- Source of record: `sites/mask-fitter/` in the orma-wiki repo — edit there, re-upload via the contents API.

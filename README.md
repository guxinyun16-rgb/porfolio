# Nebula Gu Portfolio — Vercel Static Build

This folder is ready to deploy as a plain static Vercel project.

## Required repository structure
Upload the **contents of this folder** to the repository root:

- `index.html`
- `about.html`
- `works.html`
- `experience.html`
- `vercel.json`
- `assets/`

In Vercel use:
- Application Preset: **Other**
- Root Directory: `./`
- Build Command: leave empty
- Output Directory: leave empty

The previous single-file V5 runtime-gzip/Blob loading has been removed. The interactive modules are regular same-origin iframe pages and all Base64 images are external fingerprinted assets.

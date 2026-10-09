# Verdandi — downloads

Verdandi reads broker invoices and other documents: it captures PDFs,
extracts structured data with an AI model you configure, verifies every
value, reviews what's doubtful, and exports a clean, colour-coded Excel
workbook.

## Download

**macOS (Apple Silicon, 10.15+)** — [latest release](../../releases/latest)

The app is **ad-hoc signed** (not notarized), so macOS asks for a one-time
approval on first launch:

1. Open the app once — macOS blocks it.
2. Go to **System Settings → Privacy & Security**, scroll to the Security
   section, and click **Open Anyway** next to Verdandi.
3. Open it again and confirm.

If your macOS version doesn't show that button, run:

```sh
xattr -cr /Applications/Verdandi.app
```

(On older macOS versions, right-click → **Open** also works.)

> If you installed **0.1.2** and saw "Verdandi is damaged and can't be
> opened", that build had a broken signature — install **0.1.3** or later
> instead.

**Windows** — the Windows installer is temporarily unavailable while our
build pipeline is being fixed. An older v0.1.0 build exists but predates
several important fixes; we recommend waiting for the next Windows release.

## What you need

- Your own **opencode Zen gateway key** ([opencode.ai/auth](https://opencode.ai/auth)) —
  the app asks for it on first run and stores it in your operating system's
  keychain. The app is free; you pay the model provider directly.
- No other installs. (If Xcode Command Line Tools are absent, the app
  automatically uses its bundled cross-platform OCR engine.)

## First run

1. Open the app, paste your gateway key.
2. Drop PDFs on the Run screen, pick a template, and run.
3. Review flagged values, then export the workbook.

## Legal

- [End User License Agreement](EULA.md)
- [Privacy Policy](PRIVACY.md)

## Support

akshaymsingh.work@gmail.com

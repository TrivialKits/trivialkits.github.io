# TrivialKits

**Small tools. Real problems. Zero friction.**

We build lightweight utilities that help people get things done, without installations, accounts, or unnecessary complexity.

Our principles:

- **Fast** — open a page and use it, no setup.
- **Private** — processing happens in the browser; files never leave your device.
- **Practical** — each tool does one job exceptionally well.
- **Free** — no paywalls, no sign-ups.
- **Browser-first** — nothing to install.

Because not every problem needs a platform. Sometimes you just need a tool.

## Tools

- **PDF Combiner & Compressor** — https://trivialkits.github.io/pdf-combiner/
  Merge PDFs in any order, or shrink them to a size you need. Compression keeps text and layout intact (it re-saves images and trims padded vector coordinates), with an optional flatten mode for strict size targets. Runs entirely on your device.

## What TrivialKits is for

1. **Solve small problems well.** Not every problem needs a SaaS subscription or an enterprise platform. Compress a PDF, optimize an image, format JSON, merge files.
2. **Zero friction.** No registration, no installation, no paywalls, no tutorials.
3. **Privacy first.** Whenever possible, processing happens in the browser and files never leave the user's device.
4. **One tool, one job.** Each tool does one thing exceptionally well, rather than being "the ultimate document platform."
5. **Accessible to everyone.** Built for non-technical users, colleagues, students, freelancers, and small teams.

## Structure

```
/                  landing page (this hub)
index.html
pdf-combiner/      one folder per tool
  index.html
```

To add a tool: create a new folder with an `index.html` inside it, then add a card to the root `index.html`. The link becomes `https://trivialkits.github.io/<folder>/`.

## Notes

- Each tool is a single, self-contained HTML file.
- Tools load a few libraries from a public CDN, so the first open needs an internet connection; after that most browsers cache them.
- Because everything runs client-side, these tools are safe for sensitive documents.

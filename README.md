# Support Page Setup

Use `support/index.html` as your public App Store Support URL page.

## 1) Update contact email

Edit this line in `support/index.html`:

- `YOUR_SUPPORT_EMAIL@example.com`

## 2) Publish it publicly (fast options)

### Option A: Cloudflare Pages (quickest)

1. Go to Cloudflare Pages.
2. Create a new project and upload the `support/` folder.
3. Use the generated public URL, for example:
   - `https://courtvision-support.pages.dev`
4. Put that URL in App Store Connect -> Support URL.

### Option B: Public GitHub Pages repo

1. Create a new public repo (example: `courtvision-support`).
2. Copy `support/index.html` to the root as `index.html`.
3. Enable GitHub Pages from `main` branch.
4. Use the URL, for example:
   - `https://<your-username>.github.io/courtvision-support/`

## 3) Verify before submitting

- URL loads without login.
- Page has working contact email link.
- URL is HTTPS.

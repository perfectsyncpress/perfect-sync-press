# Perfect Sync Press Astro Site

Static Astro website for insyncpub.com.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## GitHub Pages

This project includes a `CNAME` file for `insyncpub.com`.

Recommended deployment:

1. Push this repository to GitHub.
2. In GitHub, enable Pages using GitHub Actions.
3. Add the included workflow at `.github/workflows/deploy.yml`, or use Astro's GitHub Pages guide.
4. Configure DNS for `insyncpub.com` to point to GitHub Pages.
5. Enable HTTPS in GitHub Pages settings.

## Customization

Replace `public/assets/book-cover.png` with the actual book cover, preferably as `book-cover.jpg` or `book-cover.webp`, then update references in `src/pages/book.astro` and `src/pages/index.astro`.

Update retailer links in `src/components/RetailLinks.astro` when final URLs are available.

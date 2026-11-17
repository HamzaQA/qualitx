# Qualitx

Dependency-free static rebuild of qualitxinc.com using semantic HTML, CSS and a Node.js build script. No WordPress runtime, database, plugins or npm packages are required.

## Develop

Requires Node.js 20+ and Python 3 for the preview server.

```
npm run build
npm test
npm start
```

Open http://localhost:3000. Edit `content/site.json` for page content, `public/style.css` for design, and `scripts/build.mjs` for templates. Deploy `dist/` to any static host; build command: `npm run build`.

## Migration status

Includes nine public pages and three blog posts imported from the public WordPress API, original URLs, local logo and hero imagery, responsive navigation, metadata, sitemap and robots file. The layout is a new static interpretation, not a verified pixel-perfect copy. Elementor-specific widgets, forms and media layouts require visual review. Contact actions currently open the visitor's email client; there is no form submission backend. Content is maintained in Git.

The existing production domain has not been changed. Before replacing it, review all pages against the original site, configure any required form delivery and analytics, and retain a WordPress backup. Static hosting still requires routine platform and runtime maintenance, but there are no WordPress plugin updates.

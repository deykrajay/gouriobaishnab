# GouriOBaishnab

**গৌড়ীয় বৈষ্ণব জ্ঞানভাণ্ডার — GouriOBaishnab**

A Bengali research-oriented digital archive for Gaudiya Vaishnava literature, Mahajan Pada, Gouranga Leela, shastra, philosophy, sadhana, dhama, history, parampara and research.

## GitHub Pages

The repository is prepared as a static site:

- `index.html` — GitHub Pages-ready website
- `404.html` — fallback page
- `.nojekyll` — prevents Jekyll processing
- `GouriOBaishnab_Blogger_Theme.xml` — preserved Blogger upload theme

Enable **Settings → Pages → Deploy from a branch → main → / (root)**.

## Important authentication note

The current authentication UI is **browser-local demo authentication** using `localStorage` / `sessionStorage`. GitHub Pages is a static hosting platform, so this is **not secure server-side authentication**. Do not store real passwords, private member data, payment information, or other sensitive data in this demo.

For a production member/admin system, replace the browser-only auth layer with a real backend/identity provider.

## License

MIT.

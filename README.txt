# Support Page

A minimal static support page you can host for free.

## Quick publish options

### GitHub Pages (recommended)
1. Create a new repo named `myapp-support`.
2. Upload `index.html` to the repo root (or drag & drop via web).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, Branch: **main**, Folder: **/** (root).
5. Wait ~1 minute. Your URL will be: `https://<your-username>.github.io/myapp-support/`.
6. Put that URL into **App Store Connect → App Information → Support URL**.

### Netlify (drag-and-drop)
1. Go to https://app.netlify.com/drop.
2. Drag the `support_site` folder — Netlify will give you a live URL instantly.
3. Use that URL as your Support URL.

### Cloudflare Pages (optional)
1. Create a project and select the repo/folder.
2. Framework preset: **None** (static).
3. Deploy and use the generated URL.

### Google Sites / Notion (non-HTML option)
- Create a public page with your contact email and link to it. Apple accepts any working https page.

## Edit text
Open `index.html` in any editor and change titles/FAQ as you see fit.

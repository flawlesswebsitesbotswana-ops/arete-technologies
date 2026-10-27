# Aréte Technologies website

Static website (single `index.html`, no build step). Part of the Aréte Group.

## Run locally
1. Open the folder in VS Code.
2. Install the **Live Server** extension (Ritwick Dey).
3. Right-click `index.html` → **Open with Live Server**.

## Deploy (GitHub Pages)
Repo → Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / root → Save.
Site appears at `https://<your-username>.github.io/<repo-name>/`.

## Still to configure
- Contact details and social links (search `TO BE SUPPLIED` in `index.html`).
- Contact form: set `CONFIG.endpoint` in the script at the bottom of `index.html` to a server-side handler (email/CRM). GitHub Pages is static, so it cannot receive form posts by itself.
- Budget ranges: fill `CONFIG.budgets`.
- Privacy Policy: review every `REVIEW` section against actual practice and Botswana law.
- Team profiles and milestones on the About view.
- Add `favicon`, social share image, `sitemap.xml` and `robots.txt` once the domain is known.

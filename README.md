# lingyun886.github.io

Personal profile site for Ling Yun.

## What this repo contains
- `index.html` — the page to show name, avatar, bio, and contact.
- `styles.css` — styling for the page.
- `avatar.svg` — placeholder avatar (replace with a photo named `avatar.jpg` or update `index.html` to point to a hosted image).
- `CNAME` — optional custom domain file (replace `example.com` with your domain or remove if not used).

## Quick deploy (GitHub Pages)
1. Create a new repository named exactly: `lingyun886.github.io`.
2. Add/commit the files in this repo and push to GitHub.
3. GitHub will publish the site at: `https://lingyun886.github.io` (may take a minute).

### Example git commands
```bash
# from a new local folder
git init
git add .
git commit -m "Initial personal page"
# replace <your-username> with lingyun886 if using same account
git remote add origin https://github.com/lingyun886/lingyun886.github.io.git
git branch -M main
git push -u origin main
```

## Replace avatar and email
- To use a real photo: add `avatar.jpg` to the repository root and (optionally) change the `<img>` src in `index.html`.
- To set your real email: edit the small JS in `index.html` and change `user` and `host` to your values, or replace the obfuscated link with a direct `mailto:` link.

## Spam protection tips
- The page uses a small JS de-obfuscator so the raw email isn't present in the HTML.
- Alternatively, use a contact form service (Formspree, Netlify Forms) if you prefer not to publish an email.

## Custom domain
- If you have a domain, replace `CNAME` content with your domain and follow GitHub Pages custom domain DNS setup: [GitHub Pages - Custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

If you want, I can:
- Produce the exact git commands filled with your GitHub repo URL and push the files (I can run a write operation if you ask and provide repository owner).
- Replace the placeholder avatar.svg with a generated avatar from a photo URL (you can upload a photo or give a link).
- Add a contact form (Formspree) and show how to configure it.
# Kéré Alliance Foundation — Website

A static website for Kéré Alliance Foundation, a Christ-centered NGO based in Ibadan, Nigeria.

## Pages

| File | URL |
|------|-----|
| `index.html` | `/` — Home |
| `feed-the-hungry.html` | `/feed-the-hungry` — Feed the Hungry program |
| `threads-of-hope.html` | `/threads-of-hope` — Threads of Hope program |
| `shelter-housing.html` | `/shelter-housing` — Shelter & Housing program |
| `healthcare-outreach.html` | `/healthcare-outreach` — Healthcare Outreach program |
| `prison-reintegration.html` | `/prison-reintegration` — Prison & Reintegration program |

## Assets

- `kere-logo.png` — Foundation logo

## Deployment (Cloudflare Pages)

### First-time setup

1. Push this repository to GitHub (see below).
2. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com) → **Pages** → **Create a project** → **Connect to Git**.
3. Select your GitHub repository.
4. Set build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (or leave as default — the root)
5. Click **Save and Deploy**.

Cloudflare Pages will automatically deploy on every push to `main`.

### Pushing to GitHub

```bash
# From inside this folder:
git init
git add .
git commit -m "Initial site deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/kere-alliance.git
git push -u origin main
```

Then connect that repo in Cloudflare Pages as above.

### Custom domain (kere.ng)

After deployment, in Cloudflare Pages → your project → **Custom domains** → Add `kere.ng` and `www.kere.ng`. Because the domain is already on Cloudflare (or you can transfer it), DNS will be set automatically.

---

*Built for Kéré Alliance Foundation · © 2025*

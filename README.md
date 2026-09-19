# maven-stories-www

Static support & privacy pages for Maven Stories apps.

Hosted with **GitHub Pages** (no Node, no build step).

## Local preview

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Enable GitHub Pages

1. Make the repo **public** (required for free Pages), or use GitHub Pro for private Pages.
2. Repo → **Settings** → **Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` / folder: `/ (root)`
5. Save

Site URL will be:

`https://evanl01.github.io/maven-stories-www/`

### App Store Connect URLs

- Support (per app): `https://evanl01.github.io/maven-stories-www/maven-stories/`
- Privacy (company-wide): `https://evanl01.github.io/maven-stories-www/privacy.html`

### Custom domain (optional)

Add a root `CNAME` file and point DNS (CNAME) at `evanl01.github.io`, then set the custom domain under **Settings → Pages**.

## Add another app

Create a folder with a support page:

```
other-app/
  index.html      # support (how to use / contact)
```

Link it from the root `index.html`. Point App Store privacy URLs at the shared `/privacy.html`.

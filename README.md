# Susruth Pamidi – Portfolio

Static personal website (single `index.html`, no build step), deployed with GitHub Pages.

## Deploy
1. Push this folder to a GitHub repo on the `main` branch.
   Name the repo `<your-username>.github.io` to get the address `https://<your-username>.github.io/`;
   any other name gives `https://<your-username>.github.io/<repo-name>/`.
2. In the repo: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. Every push to `main` runs `.github/workflows/pages.yml` and publishes the site.

## Edit
Change `index.html`, commit and push. The site updates in about a minute.

## Custom domain (optional)
Settings → Pages → Custom domain, then add a CNAME DNS record pointing to `<your-username>.github.io`.

## Run locally
```bash
python3 -m http.server 8080
```
Open http://localhost:8080. A `Dockerfile` is also included if you want to run it as a container.

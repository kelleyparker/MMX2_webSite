Sites used to acquire resources:
IMAGES ---> http://www.spriters-resource.com/snes/megamanx2/

## GitHub Pages deployment

This repository now includes a workflow at `.github/workflows/deploy-gh-pages.yml` that deploys the site to GitHub Pages.

### One-time setup in GitHub

1. Push this repository to GitHub.
2. In your repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Ensure your default branch is one of: `main`, `master`, or `work` (or update the workflow trigger).

### Site URL format

After the workflow succeeds, your site URL will be:

`https://<your-github-username>.github.io/MMX2_webSite/`

If your repository name is different, replace `MMX2_webSite` with your actual repository name.

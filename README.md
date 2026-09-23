# Alice Wang — personal website

This repository contains a static HTML, CSS, and JavaScript website. The GitHub Actions workflow in `.github/workflows/pages.yml` publishes it to GitHub Pages when changes are pushed to `main`.

## Publish with GitHub Pages

1. Create a GitHub repository and push this folder to its `main` branch.
2. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
3. After the first successful workflow run, the site will be available at the GitHub Pages URL shown in the repository's Pages settings.
4. To use `alicenywang.com`, first add and verify the domain in GitHub Pages settings. Then set `alicenywang.com` as the site's custom domain.
5. In Spaceship DNS, point the apex domain (`@`) to GitHub Pages with A records `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and `185.199.111.153`. Add a CNAME record for `www` pointing to `<your-github-username>.github.io`.

GitHub Pages is available for free on public repositories. On GitHub Free, a private repository cannot be used to publish a Pages site.

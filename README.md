# Holberton Challenge
This website was created as a part of Holberton School's Admission process.
Schools like Holberton and Make School represent a new age in education &mdash; they do not require up-front tuition, and instead take a cut of your salary for a few years.
As a student, you never drown in student-loan debt.

## Set Up Locally
This is a static website; no dependencies or build step are needed.
From the repository directory, start Python's built-in web server:

```powershell
py -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser.
Stop the server with `Ctrl+C`.

If `py` is not available, use `python -m http.server 8000`.

## Deploy using GitHub Pages
The site is hosted with GitHub Pages from the `main` branch at the repository root.
To publish changes:
1. Push the changes to `main`.
1. In the repository's **Settings → Pages**, set **Build and deployment** to **Deploy from a branch**, then select `main` and `/(root)`.
1. Wait for the Pages deployment to finish.
	The site should be available at [https://noltron000.github.io/holberton-challenge/](https://noltron000.github.io/holberton-challenge/).

### Using a Custom domain
To serve the project at `https://projects.nebuloid.dev/holberton-challenge/`:
1. At your DNS provider, create a `CNAME` record for `projects` pointing to `noltron000.github.io`.
1. In the **Settings → Pages** for your user-site repository (`noltron000.github.io`), set `projects.nebuloid.dev` as its custom domain.
	GitHub Pages applies a user site's custom domain to its project sites, so this repository will be available under `/holberton-challenge/`.
1. Do not set a separate custom domain on this project repository; that would override the inherited domain.
1. After DNS and Pages finish configuring, enable **Enforce HTTPS** in Pages settings and visit [https://projects.nebuloid.dev/holberton-challenge/](https://projects.nebuloid.dev/holberton-challenge/).

See GitHub's documentation on [custom domains across multiple repositories](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages#using-a-custom-domain-across-multiple-repositories) and [configuring a subdomain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-a-subdomain).

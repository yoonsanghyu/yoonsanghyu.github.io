
# Project Pages Scaffold (GitHub Pages via `docs/`)

This repository contains a **ready-to-use scaffold** for a project website under `https://yoonsanghyu.github.io/PROJECT_SLUG`.

## How to use

1. Create a new repo on GitHub (e.g., `PROJECT_SLUG`).
2. Copy this scaffold into that repo.
3. Edit `docs/_config.yml`:
   - Set `baseurl: "/PROJECT_SLUG"`
   - Set `url: "https://yoonsanghyu.github.io"` (or your custom domain)
   - Change `title` and `description`.
4. Go to **Settings → Pages** and set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/docs`
5. Wait a minute for build → Your site becomes available at  
   `https://yoonsanghyu.github.io/PROJECT_SLUG`.

## Notes
- Put images under `docs/assets/img/` and reference as `{{ site.baseurl }}/assets/img/your.png`.
- Internal links: prefix with `{{ site.baseurl }}` to work both locally and on GitHub Pages.
- If you use a **custom domain**, add a `CNAME` file in `docs/` with your domain and set it in **Pages** settings.

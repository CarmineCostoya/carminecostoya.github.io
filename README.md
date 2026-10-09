# Carmine Costoya Portfolio

A static Jekyll portfolio published at [carminecostoya.github.io](https://carminecostoya.github.io/).

## Site structure

- `index.md` — homepage
- `about.md` — biography and education
- `experience.md` — professional experience
- `contact.md` — public contact route
- `_layouts/` and `_includes/` — reusable page structure
- `assets/` — styles and favicon
- `_config.yml` — Jekyll and GitHub Pages settings

All publishable files live at the repository root so GitHub Pages can deploy from `main` and `/ (root)`.

## Update the content

Edit the Markdown file for the relevant page. Each page begins with YAML front matter that controls its title, description, layout, and URL. Shared navigation and footer content live in `_includes/`; visual styles live in `assets/css/main.css`.

## Preview locally

1. Install a current Ruby and Bundler.
2. From the repository root, run `bundle install`.
3. Run `bundle exec jekyll serve`.
4. Open `http://127.0.0.1:4000/`.

The generated `_site/` directory is ignored and should not be committed.

## Make changes with Git

Create a branch from an up-to-date `main`, make one focused improvement, preview it, then commit and push the branch. Open a pull request on GitHub, review and comment on the diff, and merge it into `main`. Pull the updated `main` before starting the next change.

## Run Lighthouse

1. Open the published site in Chrome.
2. Open Developer Tools and select **Lighthouse**.
3. Test the desktop and mobile experiences.
4. Confirm scores of at least 90 for Performance, Accessibility, Best Practices, and SEO.

Also inspect each page at 375px and 1280px widths, test every navigation link, and complete a keyboard-only pass.

## GitHub Pages settings

In the repository's **Settings → Pages** screen, choose:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

The configured `url` is `https://carminecostoya.github.io` and `baseurl` is empty because this is a GitHub user site.

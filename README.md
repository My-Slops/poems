# Poems

A Jekyll site using the Minima theme for GitHub Pages.

## Local Development

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Run the site locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Open http://localhost:4000 in your browser.

## GitHub Pages Setup

1. Push this repository to GitHub.
2. Go to **Settings > Pages** in your repository.
3. Under "Source", select "Deploy from a branch".
4. Select the `main` or `master` branch and `/ (root)` folder.
5. Click **Save**.

Your site will be published at `https://<username>.github.io/poems`.

## Adding Content

- **Posts**: Create new `.md` files in the `_posts/` directory with the format `YYYY-MM-DD-title.md`.
- **Pages**: Create new `.md` files in the root directory with a `permalink` in the front matter.

## Customization

Edit `_config.yml` to customize:
- Site title and description
- Author information
- Social links
- Theme skin (classic, dark, solarized, solarized-dark)

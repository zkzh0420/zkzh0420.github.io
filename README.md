# Personal Academic Homepage

Single-page bilingual Jekyll site for GitHub Pages.

## Structure

```text
_config.yml          # site and author settings
index.html           # English home page
zh/index.html        # Chinese home page
_includes/           # navigation and footer
_layouts/            # shared layouts
assets/css/style.css # site styling
img/Profile.jpg      # personal photo
files/               # optional CV or papers
```

## Edit Points

- Update your name and GitHub Pages URL in `_config.yml`.
- Replace the homepage text in `index.html` and `zh/index.html`.
- Put optional files such as a CV in `files/` and link them from the homepage if needed.

## Run Locally

```bash
bundle install
bundle exec jekyll serve
```

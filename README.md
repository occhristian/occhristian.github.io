# Christian Okeke Portfolio

A Jekyll/GitHub Pages portfolio site for `occhristian.github.io`.

## How to use

1. Copy these files into your `occhristian.github.io` repository.
2. Put new articles inside `_posts` using the format `YYYY-MM-DD-title.md`.
3. Edit `_data/projects.yml` to add or change projects.
4. Push to GitHub.

```bash
git add --all
git commit -m "Build portfolio site"
git push origin main
```

GitHub Pages will build the site automatically.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

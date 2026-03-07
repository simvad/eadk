# Effective Altruism Denmark

Website for [effectivealtruism.dk](https://effectivealtruism.dk), built with [Hugo](https://gohugo.io/).

## Setup

1. Install Hugo: https://gohugo.io/installation/
2. Clone the repo: `git clone git@github.com:simvad/eadk.git`
3. Run locally: `hugo server`
4. View at http://localhost:1313

## Contributing

All changes go through branches and pull requests — never push directly to `main`.

```
git checkout main
git pull
git checkout -b your-name/short-description
```

Make your changes, then:

```
git add -A
git commit -m "Describe what you changed"
git push -u origin your-name/short-description
```

Then open a pull request on GitHub. The site auto-deploys when a PR is merged to `main`.

## Project structure

```
content/          ← Page content (Markdown). Edit these to change text.
static/           ← Static files (favicon, CNAME)
themes/eadk/
  layouts/        ← HTML templates
  static/css/     ← Stylesheet
  static/images/  ← Site images
  static/js/      ← JavaScript
hugo.toml         ← Site config, menus, metadata
```

Most content work only requires editing files in `content/`.

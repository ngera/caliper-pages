# caliper-pages

A GitHub Pages theme that renders a repo's README and docs with the
[Caliper](https://github.com/ngera/caliper) look, plus a link back to
[all projects](https://ngera.github.io/).

## Use it in a repo

Add (or edit) `_config.yml` in the folder Pages publishes from:

```yaml
remote_theme: ngera/caliper-pages
plugins:
  - jekyll-remote-theme
```

Remove any `theme:` line. Push, and the next Pages build picks it up.

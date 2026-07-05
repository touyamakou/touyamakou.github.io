# touyama GitHub Pages

Jekyll blog for GitHub Pages with a Zenn-inspired profile page and article page.

## Local preview

```powershell
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Customize

Edit `_config.yml` for site, brand, and profile metadata.

```yml
brand:
  title: "Draft"
  icon_text: "T"
  icon_image: "/assets/images/logo.png"

profile:
  name: "touyama"
  bio: "..."
  avatar: "/assets/images/avatar.jpg"
```

Put local images under `assets/images/`.
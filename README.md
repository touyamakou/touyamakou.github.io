# touyama GitHub Pages

Jekyll blog for GitHub Pages with a Zenn-inspired profile page and article page.

## Local preview

```powershell
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Customize

Edit `_config.yml` for site, brand, profile, and social preview metadata.

```yml
brand:
  title: "Draft"
  icon_text: "T"
  icon_image: "/assets/images/logo.png"

social_preview:
  image: "/assets/images/og-default.png"
  width: 1200
  height: 630

profile:
  name: "touyama"
  bio: "..."
  avatar: "/assets/images/avatar.jpg"
```

Put local images under `assets/images/`. Posts can override the social preview image with `image: "/assets/images/post-image.png"` in front matter.

## Post topic example

Use `icon` for text or emoji icons. Use `image` only when you want an image file.

```yml
topics:
  - name: CLI
    icon: CLI
  - name: VPN
    icon: V
  - name: Unity
    image: /assets/images/topic-unity.png
```

# ICT Solved! – App Portfolio Site

Hosted at **https://ictsolved.github.io/apps/**

Built with Jekyll. Deployed via GitHub Pages from the `master` branch of the `apps` repo.

## Local development

```bash
bundle install
bundle exec jekyll serve
# → http://localhost:4000/apps/
```

## Structure

```
index.html                  # Portfolio home — add a card here for each new app
consistency/
  index.html                # App landing page (layout: app)
  privacy.md                # Privacy policy (layout: page)
assets/
  apps/
    consistency/
      icon.png              # App icon (square, min 120×120)
      screenshots/
        home.png            # Screenshot shown in phone mockup
_layouts/
  home.html                 # Portfolio home layout
  app.html                  # App landing layout
  page.html                 # Markdown sub-page layout (privacy, etc.)
```

## Adding a new app

1. Create `your-app/index.html` using `layout: app` — copy `consistency/index.html` as a template and fill in front matter (app_name, features, playstore_link, screenshot, privacy_url).
2. Create `your-app/privacy.md` using `layout: page` — copy `consistency/privacy.md` and update content.
3. Add app icon and screenshot to `assets/apps/your-app/`.
4. Add a card to `index.html`.

## Deploy

Push to the `apps` repo on GitHub (`ictsolved/apps`). GitHub Pages will build and publish automatically.

## Credits

Phone mockup and original single-app Jekyll template by [Emil Baehr](https://emilbaehr.github.io/automatic-app-landing-page/). Substantially restructured into a multi-app portfolio with custom layouts, Sass module migration, and SEO improvements.

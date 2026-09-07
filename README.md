# Cornercase QA Labs (Jekyll site)

This repo now uses a minimal Jekyll structure so you can add posts and reuse layouts. Files added by the conversion:

- _config.yml — site configuration
- _layouts/default.html — main HTML layout used by pages/posts
- _includes/head.html — head meta tags and CSS link
- assets/css/main.css — site styles
- index.md — homepage using the default layout (includes the hero gallery and services)
- _posts/2026-09-07-welcome.md — sample post

Notes:
- The site keeps the existing assets in /assets/ (logo/banner/background/images). I did not change those.
- To preview locally: install Ruby + Jekyll, run `bundle exec jekyll serve` in the repo root, then open http://127.0.0.1:4000

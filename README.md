# SALGBA Shark Tank Landing Page

Static landing page for the SALGBA Shark Tank event — Providence, RI, May 5, 2026.

## Before Deploying

Search `index.html` for `STRIPE_LINK_HERE` and replace all 4 instances with your Stripe payment link.

```bash
# macOS/Linux
sed -i '' 's|STRIPE_LINK_HERE|https://buy.stripe.com/YOUR_LINK_HERE|g' public/index.html

# Or just find-and-replace in any text editor
```

## Deploy to Render

1. Push this repo to GitHub
2. In Render dashboard → **New** → **Static Site**
3. Connect the GitHub repo
4. Render auto-detects `render.yaml` — publish directory is `./public`
5. Deploy

Custom domain: point your DNS (e.g. `salgbasharktank.validationinstitute.com`) to Render per their docs.

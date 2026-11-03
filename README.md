# thehargestacademy.com

Site for The Hargest Academy: private lessons and competition cleaning with Robin Hargest, choreography and music cutting with Brittany Hargest Prins.

A single static page (`index.html` plus `assets/`), hosted on GitHub Pages. No build step.

## Preview

Run any static server from the repo root, for example:

```bash
python3 -m http.server 4400
```

## Going live

The site currently blocks search engines because it's a preview. Before pointing the domain here:

1. Remove the `robots` meta tag in `index.html` and delete `robots.txt`.
2. Set the custom domain in the repo's Pages settings (adds a `CNAME` file).
3. Update DNS: GitHub's Pages A records for the bare domain, and a `www` CNAME to `hiimkyle.github.io`. Leave the email (MX/SPF/DKIM) records alone.

Keep the studio's street address off the site. Copy says "minutes from downtown Franklin."

# thehargestacademy.com

Site for The Hargest Academy: private lessons and competition cleaning with Robin Hargest, choreography and music cutting with Brittany Hargest Prins.

A single static page (`index.html` plus `assets/`), hosted on GitHub Pages. No build step.

## Preview

Run any static server from the repo root, for example:

```bash
python3 -m http.server 4400
```

## Domain

Live at https://www.thehargestacademy.com (the `CNAME` file). The bare domain redirects to `www`.

- **thehargestacademy.com**: DNS at DreamHost, set to DNS Only. The bare domain has GitHub's four Pages A records (`185.199.108–111.153`) and `www` is a CNAME to `hiimkyle.github.io`. The mailboxes are at DreamHost, so leave the `mail`, `webmail`, `mailboxes`, MX, SPF and DKIM records alone.
- **hargestacademy.com**: DNS at GoDaddy, which forwards it to thehargestacademy.com.

Keep the studio's street address off the site. Copy says "minutes from downtown Franklin."

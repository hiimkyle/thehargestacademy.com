# thehargestacademy.com

Site for The Hargest Academy: private lessons and competition cleaning with Robin Hargest, choreography and music cutting with Brittany Hargest Prins.

A single static page (`index.html` plus `assets/`, and a branded `404.html`), hosted on Netlify. No build step: Netlify publishes the repo root and redeploys on every push to `main`.

## Preview

Run any static server from the repo root, for example:

```bash
python3 -m http.server 4400
```

## Domain

Live at https://thehargestacademy.com. `www` redirects to the bare domain (Netlify's primary domain; it wouldn't switch to `www`), and Netlify provides the HTTPS certificate (Let's Encrypt).

- **Netlify**: project `thehargestacademy` (https://thehargestacademy.netlify.app) on the hiimkyle team, linked to this repo. Both domains are set under Domain management.
- **thehargestacademy.com**: DNS at DreamHost, set to DNS Only. The bare domain has one A record, `75.2.60.5` (Netlify), and `www` is a CNAME to `thehargestacademy.netlify.app`. The mailboxes are at DreamHost, so leave the `mail`, `webmail`, `mailboxes`, MX, SPF and DKIM records alone.
- **GitHub verified domain**: the TXT record `_github-pages-challenge-hiimkyle` is left over from GitHub Pages hosting. It stops any other GitHub account from claiming the domain. Leave it in place.
- **Registration**: both domains are registered at GoDaddy and renew on March 20, 2027.
- **hargestacademy.com**: DNS at GoDaddy, which forwards it to thehargestacademy.com.

Keep the studio's street address off the site. Copy says "minutes from downtown Franklin."

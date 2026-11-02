# Chess Cooldown website

Public website and privacy policy for the Chess Cooldown Chrome extension.

The site is intentionally plain static HTML and CSS: no build step, frameworks, JavaScript, analytics, cookies, trackers, external fonts, CDNs, or forms.

## Local preview

From the repository root, run any basic static file server, for example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Deployment

GitHub Pages deploys directly from the `main` branch at the repository root (`/`). Pushing a commit to `main` updates the site automatically.

- Site: <https://benoit-dev.github.io/chess-cooldown-site/>
- Privacy policy: <https://benoit-dev.github.io/chess-cooldown-site/privacy/>

## Open placeholders

- Replace `CONTACT_EMAIL_TBD` in `privacy/index.html` with the public support/privacy contact address.
- Replace the clearly marked Chrome Web Store placeholder in `index.html` after the listing is approved.

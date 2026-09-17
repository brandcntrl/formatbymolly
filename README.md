# format. by molly — prototype

A working prototype of the app, as one page. Everything runs on the phone; nothing is sent anywhere. Saves, plans, notes and certificates are kept in the phone's browser storage.

## put it online (GitHub Pages)

1. Create a new repository on GitHub (for example `formatbymolly-app`). Public is fine.
2. Upload every file in this folder to the root of the repository: `index.html`, `manifest.webmanifest`, `icon-512.png`, `icon-180.png`, `favicon.png`, `qr.html`, `qr.png`.
3. In the repository: Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. After a minute the site is live at `https://<your-username>.github.io/formatbymolly-app/`.

## link it from formatbymolly.com

Either point a path or subdomain at the GitHub page:

- **Simplest:** add a redirect on formatbymolly.com from `/app` to the GitHub Pages address.
- **Cleaner:** use a subdomain such as `app.formatbymolly.com`. In the repository add a file called `CNAME` containing `app.formatbymolly.com`, and in your domain's DNS add a CNAME record for `app` pointing to `<your-username>.github.io`. GitHub then serves it at that address with https.

## the qr code

`qr.png` points to `https://formatbymolly.com/app`. If the final link is different, open `qr.html` (it is also on the site), type the link, and screenshot the code.

## on her phone

Open the link in Safari, then Share → Add to Home Screen. It opens full screen with the format. icon, like an app.

## resetting

Settings (three dots on the member pass) → start over clears everything saved on that phone.

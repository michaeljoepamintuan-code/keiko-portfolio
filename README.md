# Keiko Marie A. Nepacena — Portfolio

Personal portfolio site: HR Head · People & Culture Leader.

Plain static site (no build step): `index.html`, `styles.css`, `assets/`.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy on Vercel

1. Push this folder to a GitHub repo.
2. In Vercel: **Add New → Project → Import** the repo.
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Deploy.

## Add a profile photo

Save the photo as `assets/photo.jpg`, then in `index.html` replace
`<div class="portrait"><span>KN</span></div>` with
`<div class="portrait"><img src="assets/photo.jpg" alt="Keiko Marie A. Nepacena" /></div>`.

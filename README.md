# K4 Kayak

A small, static starter website for K4 Kayak. It uses plain HTML and CSS, so there is no build step or dependency installation.

## Run locally

From this folder, run:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Publish with Netlify

The included `netlify.toml` sets the publish directory to the project root. There is no build command.

To connect automatic deploys, push this folder to a GitHub repository, then in Netlify choose **Add new site** > **Import an existing project** and select that repository. Netlify will deploy the site and rebuild it when changes are pushed.

The photography is loaded from Unsplash and the typefaces from Google Fonts; replace these with approved K4 Kayak assets before launch.
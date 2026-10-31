# VOIDFOUNDRY — GitHub Pages edition

This is the **static, ready-to-upload** version of VOIDFOUNDRY. No server is needed for the core generator.

## Publish with GitHub Pages

1. Sign into https://github.com and select **New repository**.
2. Name it `voidfoundry`, set visibility to **Public**, and create it.
3. In your repository, choose **Add file → Upload files**.
4. Upload the **contents of this folder** — `index.html`, `styles.css`, `src/`, `assets/`, `.nojekyll` and `README.md` — to the **root of the repository**. Do not upload only the ZIP, and do not nest the files inside an extra `voidfoundry` folder.
5. Commit the files.
6. Select **Settings → Pages**, then under **Build and deployment** choose **Deploy from a branch**, branch **main**, folder **/(root)**, and **Save**.
7. Your site URL will follow `https://YOUR-USERNAME.github.io/voidfoundry/`.

## Features available on GitHub Pages

- Chapter generation with random or selected attributes
- World, character and fauna vector illustrations
- Chapter company markings and heraldry
- Narrative dossiers and chronology
- Browser-based saving (local to the visitor's browser and device)
- Seed sharing using generated website URLs
- Printable dossier export

## Not available on GitHub Pages alone

The **Enhance Lore** and **Generate AI Art** actions need a separately hosted backend with a securely stored API key. The buttons will explain the limitation when pressed. Do not put any OpenAI API key, `.env` file or secret anywhere in a publicly accessible GitHub Pages repository.

To add public AI features later, deploy a protected API service on a platform that supports Node.js/serverless functions, and configure quotas, authentication and abuse protections.

## Editorial and IP note

VOIDFOUNDRY is an unofficial fan project. Its generated Chapter material is original and only designed to be compatible with selected established lore; it is not an official canon compendium. Check Games Workshop's applicable fan-content and IP policies before public launch or monetisation.

# DAEV TECH website

A lightweight, responsive static website for DAEV TECH. It uses plain HTML and CSS: there is no build step, runtime dependency, external font, or third-party script.

## Preview

Open `index.html` in a browser, or serve the repository root with any static web server.

## Site sections

- Services: software and web development, project assistance, CCTV installation, laptop repairs, Windows installation, and tech support.
- Approach: clarify goals and scope before work starts.
- Contact: direct phone, WhatsApp, and email links.

## Contact details shown on the site

- Phone: +263 786 405 808
- WhatsApp: +263 715 306 724
- Email: daevmassy@gmail.com

The service wording avoids fixed pricing or response-time promises; confirm availability, requirements, licensing and any quote directly with DAEV TECH.

## Service photography

The service photos are illustrative stock images, not photographs of DAEV TECH installations or client projects. They are stored locally in `assets/services/`, so the site does not make third-party image requests at runtime. Images are from Unsplash and used under the [Unsplash License](https://unsplash.com/license).

## GitHub Pages

The static site is published from the `main` branch and repository root at <https://daevmassy.github.io/DAEVTECH/>.

## Render

This repository includes a root-level `render.yaml` Blueprint for Render. It configures the site as a static site that deploys from the `main` branch and publishes the repository root. No app server, build dependencies, environment variables, or secrets are required.

To create the Render service, sign in to Render, choose **New → Blueprint**, connect `daevmassy/DAEVTECH`, and apply the detected Blueprint. Render will then provide the site's `onrender.com` URL. The existing GitHub Pages site is unchanged.

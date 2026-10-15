# Dina Fahmi — Creative Portfolio

A responsive portfolio for Dina Fahmi: creative direction, branding, fashion, art and illustration, with links to her music and video channels.

## Open

Open **index.html** directly in a browser. Everything needed for the page, including artwork, styles and scripts, is embedded in that file. No installation, build step, Google Sheet, backend or API key is required.

**Dina_Fahmi_Portfolio.txt** contains the identical complete HTML source, provided as a text download. Rename the downloaded text file to `index.html` to use it.

## Publish with GitHub Pages

In this repository, go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, select **main** and **/ (root)**, then **Save**.

The expected address after GitHub confirms deployment is:
https://fady-gendi.github.io/Dina/

Committing the files alone does not enable GitHub Pages.

## Features

- Responsive layouts for phones, tablets and desktops.
- Seventeen selected projects, filterable by Branding, Fashion, and Art & illustration.
- Accessible project dialogs, with selected gallery images for Bites and Christine Massarany.
- Direct links to the complete Behance projects.
- About section, selected professional experience, SoundCloud and Vimeo links.
- Keyboard navigation, native dialog focus management and reduced-motion support.
- No tracking, analytics, contact form or third-party scripts.

## Content and images

Content is based on Dina's public Behance profile and published projects. See **sources.json** for source links. Artwork belongs to its respective rights holders. Images are embedded as optimized WebP files so the portfolio does not depend on Behance image hosting at runtime.

Some project pages were unavailable during collection. Those projects display their verified published cover and link to the complete project on Behance. Contact uses Dina's public Behance profile; no email address was guessed. Audio and video link to Dina's channels instead of inventing media samples.

## Editing

The deployed site is self-contained in `index.html`. Project metadata and images for the dialog are in the `portfolio-data` JSON block near the bottom. Grid cards are normal HTML, so source links work with JavaScript disabled. Keep the `.txt` source copy synchronized after edits.

## Verification

Checked HTML structure, embedded image decoding, internal anchor targets, project counts and source links, JavaScript syntax, and filtering/menu/dialog interactions using a DOM harness. Browser rendering was not verified in this environment.

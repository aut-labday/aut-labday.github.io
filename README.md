# AUT Lab Day 2026

A lightweight, static, bilingual (German-first) workshop website for Fraunhofer IPK × TU Berlin.

## Deployment at the root URL

The public repository **`aut-labday/aut-labday.github.io`** is created and the website files are committed to the default branch (`main`). Go to **Settings → Pages → Build and deployment** and select **Deploy from a branch**, `main`, `/(root)`. The resulting URL is **https://aut-labday.github.io/**.

GitHub organization ownership alone does not create or publish the site. A repository and Pages setting are required.

## Editing

- All event wording is contained in `index.html`.
- German is the default HTML; English strings live in the `en` object near the end of the file.
- Every editable bilingual content element has a `data-i18n` key.
- Dates, venues, research-talk allocations, and challenge details are provisional and should be confirmed before public invitations.
- The archived 2025 edition is only a placeholder; no private slides or posters are published.

## Institutional logos / branding

The header includes two remotely loaded institutional logos with text fallbacks:
- Fraunhofer wordmark via Wikimedia Commons Special:Redirect.
- TU Berlin's long logo via an official publicly listed TU Berlin SVN file.

These files are not redistributed in this repo. The respective institutions' trademark and corporate design rules still apply to public use. Obtain institutional permission/approved assets before public promotion if required. If a logo fails to load, a typographic fallback is shown.

## Security

This is a public static site. Do not add confidential research material, unpublished presentations, personal contact information, or private attendee lists. If such information is needed, link to an authorized internal platform.

## Technology

No framework, third-party JavaScript, cookies, analytics, web fonts, or build step. JavaScript is used only for the language switch; first-time visitors see German. Content and layout work without JavaScript.
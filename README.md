# AUT Lab Day 2026

A lightweight, static, bilingual (German-first) workshop website for Fraunhofer IPK × TU Berlin.

## Deployment at the root URL

This repository is published under **https://aut-labday.github.io/**. In **Settings → Pages → Build and deployment**, use **Deploy from a branch**, `main`, `/(root)`.

GitHub Pages must be enabled in repository settings for the site to go live.

## Editing

- All event wording is contained in `index.html`.
- German is the default HTML; English strings live in the `en` object near the end of the file.
- Every editable bilingual content element has a `data-i18n` key.
- Dates, venues, research-talk allocations, and challenge details are provisional and should be confirmed before public invitations.
- Past editions and the archive have been removed until approved archival content is actually available.
- The RSVP form is under `Teilnahme & Beiträge`. It is bilingual, with name, email, attendance, role (including student, intern, administration), affiliation (OE410/OE420/TU Berlin/other), separate poster/demo/talk options, mandatory proposed topic/title for every selected contribution, and optional additional details.
- The form asks for **proposed** contributions only: final presentation slots and materials are coordinated separately.
- Students are asked to coordinate topic and format with their supervisor. Poster guidance reflects 2025 practice: A2 posters, a short personal profile with name and photo, visuals and bullet points, research content rather than administrative detail, flexible template. A printed poster/demo or slide file is **not** uploaded in this sign-up form.
- The 2025 submission deadlines were Oct 31 (topic/format) and Nov 28 (final posters/slides). They are **not automatically carried over into 2026**; the public page says 2026 deadlines remain to be confirmed. For 2026 planning, consider Friday Oct 30 and Friday Nov 27 rather than the weekend dates.

## Registration form

GitHub Pages has no backend to receive responses. The form therefore **does not send registrations from the site itself**. Clicking **E-Mail vorbereiten / Prepare email** opens the visitor's email program with a prefilled message to the organizer mailbox defined in `registrationEmail` in `index.html`. The visitor must send that message. A **Copy** button is available as a fallback. No RSVP data is stored on the website.

The configured destination is `vivek.chavan@ipk.fraunhofer.de`, as explicitly specified by the organizer. For a centralized spreadsheet and more convenient mobile registration, create a Google Form (or approved institutional form), then link to it from this section. Do not publish a fake/placeholder Google Form URL.

## Institutional logos / branding

The header includes two remotely loaded institutional logos with text fallbacks:
- Fraunhofer wordmark via Wikimedia Commons Special:Redirect.
- TU Berlin's long logo via an official publicly listed TU Berlin SVN file.

These files are not redistributed in this repo. The respective institutions' trademark and corporate design rules still apply to public use. Obtain institutional permission/approved assets before public promotion if required. If a logo fails to load, a typographic fallback is shown.

## Security

This is a public static site. Do not add confidential research material, unpublished presentations, or private attendee lists. If such information is needed, link to an authorized internal platform.

## Technology

No framework, third-party JavaScript, cookies, analytics, web fonts, or build step. JavaScript is used for the language switch and to prefill a mailto message or copy answers; first-time visitors see German. Content and layout work without JavaScript.
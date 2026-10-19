# AUT Lab Day 2026

A lightweight, static, bilingual (German-first) workshop website for Fraunhofer IPK × TU Berlin.

## Deployment at the root URL

This repository is published under **https://aut-labday.github.io/**. In **Settings → Pages → Build and deployment**, use **Deploy from a branch**, `main`, `/(root)`.

GitHub Pages must be enabled in repository settings for the site to go live.

## Editing

- All event wording is contained in `index.html`.
- German is the default HTML; English strings live in the `en` object near the end of the file.
- Every editable bilingual content element has a `data-i18n` key.
- The date **10 December 2026** and two adjacent rooms **PWZ2/PWZ1** are booked. The website lists both booked rooms for poster sessions and the challenge, while exact poster layout, start time of the departmental meeting, Oli's talk length, speaker allocation, deadlines and challenge scenario remain **provisional**.
- Past editions and the archive have been removed until approved archival content is actually available.
- The RSVP form is under `Teilnahme & Beiträge`. It is bilingual, with name, email, attendance, role (including student, intern, administration), affiliation (OE410/OE420/TU Berlin/other), separate poster/demo/talk options, mandatory proposed topic/title for every selected contribution, and optional additional details.
- The form asks for **proposed** contributions only: final presentation slots and materials are coordinated separately.
- Students are asked to coordinate topic and format with their supervisor. Poster guidance reflects 2025 practice: A2 posters, a short personal profile with name and photo, visuals and bullet points, research content rather than administrative detail, flexible template. A printed poster/demo or slide file is **not** uploaded in this sign-up form.
- The 2025 submission deadlines were October 31 (topic/format) and November 28 (final posters/slides). These are not copied as fixed 2026 deadlines. The website currently proposes **November 6** for provisional topics/formats, **November 27** for final print-ready A2 posters, and **December 4** for final presentation slides; these dates remain subject to confirmation.

## 2026 venue, instructions and materials

The public site has a **FAQ** based on the 2025 info deck and separate bilingual, clickable **Studierende / HiWis** and **WiMis / Forschende** instruction tabs.

- **Confirmed rooms:** adjacent **PWZ2** (larger, main talk/plenary room) and **PWZ1** on December 10. Both rooms are planned for the two poster/demo sessions and the Industrial Automation Challenge. Room arrangement and poster mounting logistics require coordination. The **Christmas gathering starts at 17:00 in room 457**.
- Student poster / demo: **A2 poster** or a short demo, coordinate topic/format with a supervising WiMi, include a profile with name and photo, and focus on scientific/technical images and a few concise bullet points instead of organizational information. The downloadable poster template is optional. **Two dedicated 30-minute poster/demo sessions** provide time for informal browsing and discussion; there is no formal full-audience poster talk. Final digital poster files are collected for coordinated printing; the submission mechanism remains to be announced.
- WiMi / researchers: two **45-minute open presentation blocks**, with volunteers first. A short technical highlight, preferably supported by a strong image, is more important than administrative project metadata. Earlier events featured both **3-minute/one-slide project spotlights (2023)** and **10-minute talk + 5-minute Q&A (2025)**; no single-speaker format is fixed for 2026. TU Berlin research contributions are explicitly welcome; number and duration of talks will be finalized after registrations.
- **Proposed, not confirmed 2026 dates:** Friday **November 6** for preliminary topics and formats; Friday **November 27** for final posters; Friday **December 4** for final research slides. Early registration is encouraged even before November 6.
- The supplied **original A2 PowerPoint poster template** has seven layout slides. It is **not a WiMi talk slide template**.
- **Poster template download is active:** the original A2 PowerPoint has been uploaded to `assets/Labday_IPK_IWF_Postervorlage_A2_mit_Steckbrief.pptx` and is directly linked in the student instructions. Do not replace it without checking public redistribution approval.

## Provisional agenda

The homepage currently proposes a **09:15–10:15** departmental meeting (early start not yet confirmed), **10:30–11:00** Jörg Krüger keynote (title to follow), **11:00–11:45** open research block I, **11:45–12:15** poster/demo session I (PWZ1 + PWZ2), a **separate 12:15–13:00 lunch break**, Oli’s confirmed talk **“(Miss)Erfolgreich – Lektionen aus 13 Jahren Fraunhofer”** at **13:00–13:25** (25-minute allocation proposed), **13:25–14:10** open research block II, **14:10–14:20** short break/team transition, **14:20–15:50** Industrial Automation Challenge (both rooms), **15:50–16:20** poster/demo session II (both rooms), and **16:20–16:30** informal **F1 Score Quiz** and closing among the posters (PWZ1 and PWZ2). This ends the technical program **30 minutes** before the **17:00 Christmas gathering in room 457**.

The agenda is an invitation to register, not a fixed speaker allocation. Interested researchers can volunteer without knowing their final titles.

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
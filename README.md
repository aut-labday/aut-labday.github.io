# AUT Lab Day 2026

Website: https://aut-labday.github.io/  
Repository: `aut-labday/aut-labday.github.io`

A lightweight bilingual (German default, English toggle) static website for the joint Fraunhofer IPK OE410/OE420 and TU Berlin research day on **Thursday, 10 December 2026**.

## Event information

- Venue: adjacent rooms **PWZ2** (main talks/plenary) and **PWZ1**. Posters, demos and the workshop use both rooms.
- The 09:15–10:15 departmental meeting, morning keynote by Prof. Jörg Krüger, two 45-minute research-talk blocks, two 30-minute poster/demo sessions, and Oliver Heimann's talk are on the agenda.
- **14:20–15:50: AUT Ideenwerkstatt / AUT Ideas Workshop.** Small mixed groups work on actual research questions, technical challenges or possible applications relevant to the participating groups. They consider the potential value, technical feasibility, a possible approach and a first useful next step, then share their ideas. Specific starting topics will be introduced closer to the event, informed by the groups' ongoing work. It is **not** a fictional industrial-customer challenge or a competition.
- **16:20–16:30:** Short F1-Score-Quiz and closing near the posters.
- **From 17:00:** Christmas celebration in **room 457**. The Lab Day ends at 16:30.
- The published schedule is preliminary; speaker contributions and exact workshop topics can be updated as preparations progress.

## Contributing

The website has separate **Studierende / HiWis** and **WiMis / Forschende** tabs.

- Students: A2 research poster or short demo; coordinate topic and format with supervisor. Use technical images and concise bullet points. Two open poster/demo sessions. The downloadable A2 PowerPoint template is in `assets/Labday_IPK_IWF_Postervorlage_A2_mit_Steckbrief.pptx` and is optional. Finished posters are collected for printing.
- Researchers: Volunteer to give project talks in the two 45-minute research blocks. Individual talk lengths and allocations depend on registrations.
- Currently displayed dates: **6 November** for proposed topics and formats, **27 November** for poster files, **4 December** for talk slides. Attendees can register earlier with a working title.

## Registration

The registration form is integrated with the website's language toggle.

The website uses **email-based registration**, not a hosted form backend. It prepares a structured message addressed to `vivek.chavan@ipk.fraunhofer.de` with a stable subject prefix (`Lab Day 2026`). The participant **must send the prepared email** to register. A copy option is also provided. Responses are not stored on GitHub Pages.

The preferred processing workflow is an Outlook inbox rule that moves messages with `Lab Day 2026` in the subject to a dedicated folder. The folder can be exported for consolidated registration analysis, retaining individual messages as a record for participants and organizers.

Keep the form's bilingual field labels, required contribution topics and stable email format when editing.

## Website maintenance

- The public website is published from `main` at the repository root using GitHub Pages.
- All HTML, CSS and JS are in `index.html`. German content lives in the HTML; English translations are in the `en` object within the inline script.
- Elements with `data-i18n` should have corresponding English keys.
- The page uses no external JS dependencies, web fonts, cookies or analytics.
- Do not put private attendee information, unpublished research materials or confidential case details on the public website.
- Institutional logos are loaded remotely with text fallbacks; respect their owners' branding requirements.

## Maintenance checks

After editing `index.html`, verify JavaScript syntax, all `data-i18n` keys, the DE/EN toggle, registration mail generation, A2 template link, times and room numbers. Avoid adding administrative planning commentary to the public page.

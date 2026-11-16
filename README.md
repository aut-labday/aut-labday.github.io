# AUT Lab Day 2026

Website: https://aut-labday.github.io/  
Repository: `aut-labday/aut-labday.github.io`

A lightweight bilingual (German default, English toggle) static website for the joint Fraunhofer IPK OE410/OE420 and TU Berlin research day on **Thursday, 10 December 2026**.

## Event information

- Venue: **PWZ3** for talks and plenary sessions; **PWZ1/PWZ2** for posters and monitor presentations; **laboratories 071/073** for demonstrations by arrangement. The workshop uses PWZ1/PWZ2.
- The 09:15–10:15 departmental meeting, morning keynote by Prof. Jörg Krüger, two 45-minute research-talk blocks, two 30-minute poster/demo sessions, and Oliver Heimann's talk are on the agenda.
- **14:20–15:50: AUT Ideenwerkstatt / AUT Ideas Workshop.** Small mixed groups work on actual research questions, technical challenges or possible applications relevant to the participating groups. They consider the potential value, technical feasibility, a possible approach and a first useful next step, then share their ideas. Specific starting topics will be introduced closer to the event, informed by the groups' ongoing work. It is **not** a fictional industrial-customer challenge or a competition.
- **16:20–16:30:** Short online F1-Score-Quiz and closing.
- **From 17:00:** Christmas celebration in **room 457**. The Lab Day ends at 16:30.
- The published schedule is preliminary; speaker contributions and exact workshop topics can be updated as preparations progress.

## Contributing

The website has separate **Studierende / HiWis** and **WiMis / Forschende** tabs.

- Students, student assistants and interns: A2 research poster, limited screen/video presentation, or laboratory demo; coordinate topic and format with supervisor. Finished A2 posters must be delivered as **PDF by 27 November** for printing. Template: `assets/Labday_IPK_IWF_Postervorlage_A2_mit_Steckbrief.pptx`. Screen slots are allocated in registration order; lab demos require advance setup and support information.
- Researchers: Volunteer to give project talks in the two 45-minute research blocks. Individual talk lengths and allocations depend on registrations.
- Current website asks participants to register topics now, submit final **poster PDFs by 27 November**, and submit talk slides by **4 December**.

## Registration

The registration form is integrated with the website's language toggle.

The website uses **email-based registration**, not a hosted form backend. It prepares a structured message addressed to `vivek.chavan@ipk.fraunhofer.de` with a stable subject prefix (`Lab Day 2026`). The participant **must send the prepared email** to register. A copy option is also provided. Responses are not stored on GitHub Pages.

The preferred processing workflow is an Outlook inbox rule that moves messages with `Lab Day 2026` in the subject to a dedicated folder. The folder can be exported for consolidated registration analysis, retaining individual messages as a record for participants and organizers.

Keep the form's bilingual field labels, required contribution topics and stable email format when editing. Student roles may select Poster, Monitor, or Demo; researcher/staff roles may select Talk or Demo. Changing roles clears ineligible selections.

## Website maintenance

- The public website is published from `main` at the repository root using GitHub Pages.
- All HTML, CSS and JS are in `index.html`. German content lives in the HTML; English translations are in the `en` object within the inline script.
- Elements with `data-i18n` should have corresponding English keys.
- The page uses no external JS dependencies, web fonts, cookies or analytics.
- Do not put private attendee information, unpublished research materials or confidential case details on the public website.
- Institutional logos are loaded remotely with text fallbacks; respect their owners' branding requirements.

## Maintenance checks

After editing `index.html`, verify JavaScript syntax, all `data-i18n` keys, the DE/EN toggle, registration mail generation, A2 template link, times and room numbers. Avoid adding administrative planning commentary to the public page.

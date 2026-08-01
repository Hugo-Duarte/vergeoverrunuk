# VergeOverrunUK content package

A responsive UK-English campaign website package for **VergeOverrunUK**.

## Current version

- Homepage written as a national evidence campaign.
- **Case Study #1** added for Blyth, Northumberland as a documented summary case.
- Dedicated summary page: `cases/case-01.html`.
- Detailed images and correspondence are not published yet; the public case page includes a documented chronology, current status, Freedom of Information transparency concerns, outcome sought, proposed Ombudsman route, right of reply and records still sought.
- The wording states that no formal court claim has been issued.
- Visible dummy buttons, inactive form endpoints and generic social links have been removed.
- Case pages support images and documents once redacted material is available.
- A privacy, redaction, corrections and right of reply page has been added: `privacy.html`.
- Public police reference numbers and other sensitive identifiers should remain in the private evidence bundle unless publication is necessary and proportionate.

## Files

- `index.html` — campaign homepage
- `styles.css` — responsive styling and case-study layout
- `script.js` — mobile menu behaviour
- `assets/logo.svg` — circular Union Jack-style community mark
- `assets/hero-verge-illustration.svg` — hero background illustration
- `assets/cases/` — folder for future redacted case images and documents
- `cases/case-01.html` — Case Study #1 documented summary page
- `privacy.html` — privacy, redaction, corrections and right of reply policy

## Publication checklist

1. Check the public pages before making them live.
2. Confirm the public domain remains `vergeoverrun.uk`.
3. Check that no private personal data appears in public HTML, images, documents or filenames.
4. Keep unredacted evidence in the private bundle.
5. Recheck the live site after publication.

## Add a new case study

1. Copy `cases/case-01.html`.
2. Rename the copy, for example `cases/case-02.html`.
3. Edit the title, status notes, facts and case narrative.
4. Keep the case summary-only until the evidence has been checked and redacted.
5. Link the new page from `index.html` by duplicating the Case Study #1 section or adding a new card.

## Add images

1. Put redacted images in `assets/cases/`.
2. Use clear filenames, for example:
   - `case-02-verge-rutting.jpg`
   - `case-02-footway-blocked.jpg`
   - `case-02-council-letter-redacted.png`
3. Add an image block to the relevant case page:

```html
<figure class="gallery-card">
  <img src="../assets/cases/case-02-verge-rutting.jpg" alt="Redacted photo showing verge rutting beside the footway" />
  <figcaption>Redacted photo showing verge rutting beside the footway.</figcaption>
</figure>
```

4. Keep captions factual: date, location context and what the image shows.

## Important publishing notes

- Treat claims as allegations unless they have been independently determined.
- Redact private personal data, faces, all identifiable children, phone numbers, signatures, direct email addresses, exact door numbers where needed, vehicle registrations and hidden metadata where appropriate.
- Keep a private, unedited evidence bundle separate from the public website, including full police or complaint reference numbers unless publication is genuinely necessary.
- Consider offering councils, developers or landowners a right of reply before publishing detailed allegations or documents.
- Keep legal-status wording accurate: do not say a Letter Before Action, council warning or claim has been submitted until it has actually been sent or filed.

## Pedestrian safety concern reporting

Case studies should record public safety impact, not just visual verge damage. Where relevant, include whether the verge overrun or pavement encroachment reaches a property exit, blocks a footway, forces pedestrians towards live traffic, or affects children, disabled residents, pushchairs or other vulnerable users.

The site is intended to support reports from council estates, private estates, new-build developments and partly adopted roads. Keep public pages summary-led until evidence has been checked and redacted.

## Privacy and redaction checklist

Before publishing images, documents, correspondence extracts or downloadable files:

1. Use locality-level location information such as `Blyth, Northumberland` unless a precise address is necessary.
2. Name organisations where relevant, but avoid unnecessary publication of individual staff names, direct emails, signatures and phone numbers.
3. Blur identifiable faces, all children, uninvolved residents, pedestrians, drivers and vehicle registration marks.
4. Remove unrelated personal material from email chains.
5. Check PDFs, Word files and images for hidden comments, tracked changes, metadata and embedded personal information.
6. Quote relevant extracts rather than publishing full unredacted correspondence bundles.
7. Keep the public page focused on documented facts, attributed statements, resident reports and questions awaiting answer.
8. Avoid stating illegality, hidden motive, exact value loss or future injury as established fact unless independently determined.

The public site can be strong and evidence-led without exposing unnecessary personal data.

## Case Study #1 — 31 July 2026 current-status update

The case page now includes:

- Current status — 31 July 2026.
- Case summary and documented records established.
- What remains disputed.
- Full chronology from 2018 onwards, including the 31 July disclosure and current procedural steps under preparation.
- Freedom of Information disclosure and outstanding transparency concerns.
- Records still sought.
- Outcome sought.
- Ombudsman complaint focus.
- Reported impact.
- What the website does not claim.
- Right of reply and corrections.
- Neutral evidence-gallery caption examples.

Footer status wording: **Case Study #1 is live as a documented summary. Supporting records and redacted evidence are being prepared for staged publication.**

Keep full police references, unredacted correspondence and private identifiers in the private evidence bundle unless publication is necessary and proportionate.

## Evidence-refinement update

Case Study #1 has been refined to separate established records, disputed matters, publication safeguards, outcome sought, Freedom of Information review issues and proposed Ombudsman points. The homepage remains high-level while detailed chronology and records sought stay on the case page.

# VergeOverrunUK GitHub Pages site

A static, responsive campaign site for **VergeOverrunUK**, configured for **vergeoverrun.uk**. It works directly on GitHub Pages with no build step.

## Current version

- Homepage rewritten around a national evidence campaign.
- **Case Study #1** added for Blyth, Northumberland as a summary-only work-in-progress case.
- Dedicated summary page: `cases/case-01.html`.
- Detailed case evidence, images, correspondence and chronology are not published yet.
- The wording now states that no formal court claim has been issued and any pre-action position is under preparation until actually sent.
- Visible dummy buttons, inactive form endpoints and generic social links have been removed.
- Case pages are ready to support images and documents once redacted material is available.

## Files

- `index.html` — campaign homepage
- `styles.css` — responsive styling and case-study layout
- `script.js` — mobile menu behaviour
- `assets/logo.svg` — circular Union Jack-style community mark
- `assets/hero-verge-illustration.svg` — hero background illustration
- `assets/cases/` — folder for future redacted case images and documents
- `cases/case-01.html` — Case Study #1 summary page
- `CNAME` — custom domain file for `vergeoverrun.uk`

## Publish or redeploy on GitHub Pages

1. Unzip the package.
2. Upload all files and folders to the root of your GitHub Pages repository.
3. Commit the changes.
4. Go to **Settings → Pages**.
5. Make sure the publishing source is your `main` branch and `/root` folder.
6. Make sure the custom domain is `vergeoverrun.uk`.
7. Wait for GitHub Pages to rebuild and then refresh the live site.

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
- Redact private personal data, faces, phone numbers, exact door numbers where needed and vehicle registrations where appropriate.
- Keep a private, unedited evidence bundle separate from the public website.
- Consider offering councils, developers or landowners a right of reply before publishing detailed allegations or documents.
- Keep legal-status wording accurate: do not say a Letter Before Action, council warning or claim has been submitted until it has actually been sent or filed.

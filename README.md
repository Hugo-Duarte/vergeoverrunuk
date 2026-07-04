# VergeOverrunUK GitHub Pages template

A static, responsive campaign site for **VergeOverrunUK**, configured for **vergeoverrun.uk**. It works directly on GitHub Pages with no build step.

## What changed in this version

- Rewrote the homepage around the national campaign message.
- Added **Case Study #1** for Blyth, Northumberland.
- Added a dedicated case page at `cases/case-01.html`.
- Added an editable case template at `cases/case-template.html`.
- Added image-gallery support using `assets/cases/`.
- Added publishing-standard notices encouraging redaction and evidence-first wording.

## Files

- `index.html` — campaign homepage
- `styles.css` — responsive styling and case-study layout
- `script.js` — mobile menu behaviour
- `assets/logo.svg` — circular Union Jack-style community mark
- `assets/verge-placeholder.svg` — editable hero background placeholder
- `assets/cases/` — case-study image/document placeholders
- `cases/case-01.html` — Case Study #1 page
- `cases/case-template.html` — copy this file when adding new cases
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

1. Copy `cases/case-template.html`.
2. Rename it, for example `cases/case-02.html`.
3. Edit the title, facts, chronology and evidence captions.
4. Add redacted images or PDFs to `assets/cases/`.
5. Link the new page from `index.html` by duplicating the Case Study #1 block or adding a new card.

## Add images

1. Put images in `assets/cases/`.
2. Use clear filenames, for example:
   - `case-02-verge-rutting.jpg`
   - `case-02-footway-blocked.jpg`
   - `case-02-council-letter-redacted.png`
3. In the relevant case page, change the `src` attribute, for example:

```html
<img src="../assets/cases/case-02-verge-rutting.jpg" alt="Redacted photo showing verge rutting beside the footway" />
```

4. Keep captions factual: date, location context, what the image shows.

## Important publishing notes

- Treat claims as allegations unless they have been independently determined.
- Redact private personal data, faces, phone numbers, exact door numbers where needed and vehicle registrations where appropriate.
- Keep a private, unedited evidence bundle separate from the public website.
- Consider offering councils, developers or landowners a right of reply before publication.
- Replace the Formspree placeholder in `index.html` with a live form endpoint, Google Form, Airtable form or secure email address.

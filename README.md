# VergeOverrunUK — website update package

Prepared: 1 August 2026

## What changed

- Rebuilt the Case 001 page as a detailed, evidence-led public record.
- Added a full chronology from 2018 to 1 August 2026.
- Added the 2022 Taylor Wimpey complaint and 2023 NCC internal referral history disclosed under FOI 11032506.
- Added the January and February 2026 pre-complaint enquiries.
- Added the Stage 1, EIR, Stage 2, July reinstatement, reported pause, final Taylor Wimpey response and FOI developments.
- Added sections for current status, evidence, outcome sought, missing records, unanswered questions, household impact, legal/procedural position, right to reply and privacy.
- Removed unsupported casualty predictions, definitive allegations of illegality and police reference numbers.
- Included selected images with metadata stripped.
- Included no analytics, forms or external dependencies.

## Deploy to GitHub Pages

1. Back up the existing repository.
2. Copy all files and folders in this package into the repository root.
3. Commit and push.
4. Confirm that GitHub Pages is configured to publish from the chosen branch/root.
5. Check the custom domain and HTTPS settings.

## Important

This is a complete replacement package based on the latest case record and available screenshots. If the live repository contains a working submission form, custom email address, analytics, extra case pages or other integrations, merge those separately rather than overwriting them blindly.

## Easy chronology updates

The chronology is also stored in `assets/chronology.json` as a structured editorial record. The public HTML is static for speed and reliability; update both the JSON and the corresponding timeline entry in `case-001/index.html` when adding future developments.

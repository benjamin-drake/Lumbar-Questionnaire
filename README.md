# Spinal Clinic Patient Questionnaire

A tablet-based patient self-report tool for NHS spinal outpatient clinics. Replaces paper pre-consultation forms with a guided digital questionnaire, completed by the patient in the waiting area before they are seen.

**Version:** v0.1-beta | **License:** GNU GPLv3 | See [CHANGELOG.md](CHANGELOG.md) for version history.

## Features

- **Multilanguage support** — full clinical translations in Urdu, Punjabi (Gurmukhi), Bengali, Polish, and Arabic, with right-to-left layout support for Urdu and Arabic
- **ODI v2.1** — Oswestry Disability Index with automatic scoring and disability band classification
- **Red flag screen** — Five validated red flag questions with automatic flagging on export
- **Medical history** — Comorbidities checklist, blood-thinning medications with named drug selection, and allergy recording
- **Body pain diagram** — Front and back silhouette with finger/stylus drawing in three colours (pain, burning, numbness)
- **VAS pain scores** — Separate back and leg visual analogue scales
- **Clinical summary** — Auto-generated plain-English paragraph summarising findings, with full ODI item table and red flag screening results, ready for EPR paste
- **PDF export** — Printable summary formatted for clinical review and EPR scanning
- **Handover screen** — Patient-facing thank you screen shown on completion; clinical summary revealed only when staff tap through
- **Kiosk mode friendly** — Designed for iPad Guided Access or equivalent tablet lockdown

## Requirements

- **No install required** — single HTML file, runs in any modern browser
- **Fully offline** — no internet connection required, ever; zero external dependencies
- **Hospital friendly** — designed for locked-down NHS networks and tablet kiosk use

## Privacy

No patient data is stored or transmitted. The questionnaire resets automatically after each patient. No server, no database, no cookies.

## Tech Stack

Vanilla HTML, CSS, and JavaScript. No frameworks, no CDN, no build process, no npm.

## Usage

**[▶ Open Questionnaire](https://benjamin-drake.github.io/Lumbar-Questionnaire/)** — opens directly in the browser, no download needed.

Or download `index.html` and open it locally, or save it directly to a tablet.

## Attribution

The Oswestry Disability Index (ODI v2.1) is reproduced for clinical use with reference to Fairbank JCT, Pynsent PB. *The Oswestry Disability Index.* Spine 2000;25(22):2940–2953. Copyright © Institute of Musculoskeletal Research and Clinical Implementation. For licensing enquiries contact IMRCI.

## Author

Benjamin Drake, South Tyneside and Sunderland NHS Foundation Trust

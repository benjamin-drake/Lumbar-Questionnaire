# Changelog

## [0.1-beta] - 2026-03-14

### Added
- Handover screen — patient-facing thank you page shown on completion; staff tap through to reveal clinical summary
- ODI item response table in clinical summary — all 10 domains with selected response text and item score
- Red flag screening table in clinical summary — all five questions shown with Yes/No, positive responses highlighted
- Reset confirmation dialog — prevents accidental data wipe in kiosk mode
- Welcome screen text now translates correctly when language is changed

### Fixed
- "Aching" label on body diagram changed to "Pain" in English and Polish
- Reset button now shows a confirmation dialog before clearing data

## [0.1-beta] - 2026-03-09

### Added
- Dermatome SVGs (front and back) replacing placeholder silhouettes; canvas enlarged to 220×490px
- Full clinical translations: Urdu, Punjabi (Gurmukhi), Bengali, Polish, Arabic — all sections including ODI, red flags, comorbidities, VAS, and UI chrome
- Separate Urdu and Punjabi language buttons; RTL layout for Urdu and Arabic
- Greyed-out Next button — unlocks live as patient completes each section; ODI section 8 correctly treated as optional
- Privacy notice updated to mention PDF export to EPR

### Fixed
- Next button not advancing after answering questions (updateNav not called from pickODI / ynClick)

## [0.0.1] - 2026-03-08

### Added
- Initial release — single HTML file, offline-capable
- ODI v2.1 (10 sections, auto-scored)
- Red flags, comorbidities, blood thinners, allergies
- Body pain diagram (finger-drawable canvas)
- VAS sliders (back and leg)
- Clinical summary with PDF export
- English, Urdu, Polish, Arabic stubs

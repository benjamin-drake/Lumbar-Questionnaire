# Changelog
 
## [0.1-beta] - 2026-03-14 (patch 2)
 
### Added
- Age calculated from DOB and displayed in PDF patient details bar alongside Hospital Number and Date of Birth
 
### Fixed
- Next button unresponsive on iOS Safari — replaced `disabled` attribute with CSS class approach which Safari handles reliably for touch targets
- PDF section headings orphaned at page bottom — each heading and its card are now wrapped in a single `break-inside:avoid` block, keeping them together across page breaks
- Erase tool painted over SVG silhouette — diagram now uses two stacked canvases (background SVG layer + transparent drawing layer); erase only affects drawing layer
- Draw button removed from toolbar and replaced with a plain non-interactive label
- VAS slider appearance now re-initialised on every visit to that section
 
## [0.1-beta] - 2026-03-14
 
### Added
- Handover screen — patient-facing thank you page shown on completion; staff tap through to reveal clinical summary
- ODI item response table in clinical summary and PDF — all 10 domains with selected response text and item score
- Red flag screening table in clinical summary and PDF — all five questions shown with Yes/No, positive responses highlighted
- Reset confirmation dialog removed — resets immediately; flow already protects against accidents
- PDF export fully redesigned to match web app aesthetic — navy header card, teal section headings, score cards, dark summary block, cream-free white background
- PDF page breaks — break-inside:avoid on all cards and score grids
- Age added to PDF patient details
- PDF text size reduced for better A4 fit
 
### Fixed
- "Aching" label on body diagram changed to "Pain" in English and Polish
 
## [0.1-beta] - 2026-03-09
 
### Added
- Dermatome SVGs (front and back) replacing placeholder silhouettes; canvas enlarged to 220×490px
- Full clinical translations: Urdu, Punjabi (Gurmukhi), Bengali, Polish, Arabic — all sections including ODI, red flags, comorbidities, VAS, and UI chrome
- Separate Urdu and Punjabi language buttons; RTL layout for Urdu and Arabic
- Greyed-out Next button — unlocks live as patient completes each section; ODI section 8 correctly treated as optional
- Privacy notice updated to mention PDF export to EPR
- Welcome screen text now translates correctly when language is changed
 
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

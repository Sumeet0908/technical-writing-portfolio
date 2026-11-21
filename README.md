# Google Drive Sample Documentation (DITA)

Unofficial sample documentation for Google Drive sharing, written in
DITA for learning and portfolio purposes. The steps were checked in
Google Drive.

## What's inside

| File | Type | Shows |
|---|---|---|
| about_sharing.dita | Concept | Concept structure, list, tip |
| upload_file.dita | Task | Steps, prerequisite, result, platform attribute |
| share_file.dita | Task | conref, keyref, audience, xref |
| sharing_settings.dita | Task | Choices inside a step |
| access_levels.dita | Reference | Tables in sections |
| common_notes.dita | Concept | Source for reused content |
| drive_guide.ditamap | Map | Topic hierarchy, key definitions |
| owner.ditaval, editor.ditaval | Filters | One source, two audiences |

## Single sourcing

- **conref:** the backup warning is written once in `common_notes.dita`
  and reused in `share_file.dita`.
- **keyref:** product names are defined once in the map and resolve at
  build time, so they look empty in the source files.
- **audience:** owner-only and editor-only notes are filtered by
  `owner.ditaval` and `editor.ditaval`.
- **platform:** web and mobile steps in `upload_file.dita`.

## Other work

- [API documentation portfolio](https://github.com/Sumeet0908/API-Documents_portfolio)

## Work log

| Date | Work |
|---|---|
| 21 Nov 2026 | Wrote the guide: 5 topics, map, filters, README |

## Planned

- Markdown version of the guide
- Flare version of the guide

## Background

Written as part of my transition into technical writing, alongside my
API documentation work.
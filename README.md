# Google Drive Sample Documentation (DITA)

Unofficial sample documentation for Google Drive sharing, created using DITA for learning and technical writing portfolio purposes. The instructions were checked in Google Drive.

## Live Documentation

The same DITA source produces audience-specific HTML5 outputs using DITA Open Toolkit (DITA-OT).

- [Owner Guide](https://sumeet0908.github.io/technical-writing-portfolio/owner/)
- [Editor Guide](https://sumeet0908.github.io/technical-writing-portfolio/editor/)

## Publishing Outputs

The DITA source has been published into multiple output formats.

| Output Format | Description | Location |
|---|---|---|
| HTML5 | Browser-based Owner and Editor guides | [Owner](docs/owner/) / [Editor](docs/editor/) |
| PDF | Downloadable documentation | [View PDF](docs/pdf/drive_guide.pdf) |
| Markdown | Standard Markdown output | [View files](docs/markdown/) |
| GitHub Markdown | GitHub-compatible Markdown output | [View files](docs/markdown_github/) |

## What's Inside

| File | Type | Shows |
|---|---|---|
| about_sharing.dita | Concept | Concept structure, lists, and tips |
| upload_file.dita | Task | Steps, prerequisites, results, and platform attributes |
| share_file.dita | Task | conref, keyref, audience, and xref |
| sharing_settings.dita | Task | Choices inside a step |
| access_levels.dita | Reference | Tables and reference information |
| common_notes.dita | Concept | Reusable content |
| drive_guide.ditamap | Map | Topic hierarchy and key definitions |
| owner.ditaval, editor.ditaval | Filters | Audience-specific publishing |

## DITA Features Demonstrated

- **DITA topic types:** Concept, Task, and Reference.
- **DITA Map:** Organizes topics into a structured documentation hierarchy.
- **conref:** Reuses the backup warning from `common_notes.dita`.
- **keyref:** Defines product names in the map and resolves them during publishing.
- **Conditional publishing:** Uses audience filters to generate Owner and Editor-specific content.
- **xref:** Creates links between related topics.
- **Multi-format publishing:** Generates HTML5, PDF, Markdown, and GitHub Markdown from the same DITA source.

## Tools Used

- DITA Open Toolkit (DITA-OT) 4.4.2
- Java JDK
- Visual Studio Code
- Git and GitHub
- GitHub Pages

## Related Work

- [API Documentation Portfolio](https://github.com/Sumeet0908/API-Documents_portfolio)

## Work Log

| Date | Work Completed |
|---|---|
| 21 Nov 2026 | Created DITA topics, map, audience filters, and initial README |
| 21 Nov 2026 | Generated Owner and Editor HTML5 outputs and published them using GitHub Pages |
| 26 Nov 2026 | Generated PDF, Markdown, and GitHub Markdown outputs |
| 26 Nov 2026 | Verified Markdown formatting and internal topic links |

## Planned

- MadCap Flare version of the guide

## Background

Created as part of my technical writing learning and portfolio development, alongside my API documentation practice.

This is an independent sample project and is not official Google documentation.
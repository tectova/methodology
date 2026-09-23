# Tectova methodology

A versioned copy of the [Tectova methodology](https://tectova.com/methodology). The site page is canonical; [`METHODOLOGY.md`](METHODOLOGY.md) is generated from the page source at the build commit of the release production serves.

- `METHODOLOGY.md` — the page text, with section anchors kept (for example `METHODOLOGY.md#the-big-four`). The release-bound publication accounting section appears on the site only.
- `CHANGELOG.md` — one entry per methodology version. The git history of this repository carries the text diff.
- `methodology.json` — `version` names the release that introduced the current text; `current_binding` names the release the export was anchored to.
- `CITATION.cff` — citation metadata; the citation URL is the site page.

A new version is issued only when the rendered text changes, including a change to a definition the page prints. Versions are dated `YYYY.MM.DD` from the UTC date of the release that introduced them, with a `.N` suffix for each further change released the same day.

## Licence

The methodology text and metadata in this repository (`README.md`, `METHODOLOGY.md`, `CHANGELOG.md`, `methodology.json` and `CITATION.cff`) are published by Tectova under the [Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). The licence text is in [LICENSE](https://github.com/tectova/methodology/blob/main/LICENSE), the unmodified CC BY 4.0 legal code; this notice is at [NOTICE](https://github.com/tectova/methodology/blob/main/NOTICE).

The licence does not extend to Tectova's underlying database, person-level records, third-party source material, images or trademarks.

## How to cite

Tectova requests attribution in this form: *Tectova, “[page title],” tectova.com/[path], accessed [date].*

Cite the methodology to its site page, https://tectova.com/methodology (for one section, add its anchor, for example `/methodology#the-big-four`), not to GitHub. When quoting a figure, retain the geography, category and as-of date displayed on the supporting page. This is a request from Tectova, not an additional condition on reuse under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode).

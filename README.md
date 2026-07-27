# Source Evaluation Checklist

A reusable, single-file checklist for critically appraising any information source — journal article, book, news story, website, dataset, or AI output.

**[Open the checklist →](https://Da-Scie.github.io/source-evaluation-checklist/)**

## What it does

Fill it in per source. It tracks a running count, gives a non-binary verdict ("holds up well" / "usable with caveats" / "gaps remain"), and lets any single red flag override a high score. Print or save to PDF to keep a record; Reset clears it for the next source.

No build step, no dependencies, no tracking, no network calls — one HTML file.

## Sections

| # | Section | Applies to |
|---|---------|-----------|
| 0 | Stop — check your reaction, set scrutiny level | any |
| 1 | Author & authority (incl. lateral reading) | any |
| 2 | Purpose & reason for writing | any |
| 3 | Currency | any |
| 4 | Evidence & reasoning | any |
| 5 | Coverage & source chain | any |
| 6 | Craft & presentation | any |
| 7 | ROBOT test | AI-involved sources only |
| — | Red flags — any one warrants caution | any |

## Why these frameworks

Checklist approaches like CRAAP are [criticised](https://files.eric.ed.gov/fulltext/EJ1329588.pdf) for encouraging box-ticking and a binary good/bad verdict. This tool borrows their coverage but deliberately avoids a pass/fail score, and adds the two moves pure checklists miss:

- **Lateral reading** — research the author and outlet *away from* their own page.
- **Tracing claims** — follow quotes, statistics, and images back to origin.

Synthesised from:

- [Cornell University Library — *Critically Analyzing Information Sources*](https://guides.library.cornell.edu/critically_analyzing/home)
- [SIFT method](https://guides.lib.uchicago.edu/c.php?g=1241077&p=9082322) (Mike Caulfield) — Stop, Investigate, Find better coverage, Trace
- [RADAR framework](https://libguides.lmu.edu/aboutRADAR) — contributes "reason for writing"
- CRAAP — Currency, Relevance, Authority, Accuracy, Purpose
- ROBOT test (McGill) — for [evaluating AI-generated content](https://guides.library.ubc.ca/GenAI/Evaluating)

## Usage

Open `index.html` in any browser, or use the hosted link above. To run locally:

```bash
git clone https://github.com/Da-Scie/source-evaluation-checklist.git
cd source-evaluation-checklist
start index.html   # macOS: open index.html
```

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Cornell's original guide is used under its [research guides use conditions](https://guides.library.cornell.edu/guideuse).

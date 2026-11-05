# Pasqyra

Fundamentals for Kosovo companies, read from audited financial statements published by
the Ministry of Finance (mf.rks-gov.net) and joined to the ARBK business registry.

*Pasqyra* is Albanian for both **mirror** and **statement** — `pasqyrat financiare` are
the financial statements this is built from.

These are private companies: no share price or market cap exists. This is a fundamentals
screener, not an exchange.

## What it shows

- **893 companies**, 660 matched to the business registry, spanning fiscal years 2013–2025
- **Screener** — each company at its own best-covered recent year
- **By fiscal year** — every company on one chosen year, so no two rows are years apart
- **Sector league table**, **Movers**, and **Data quality**

## The one rule

Only figures an arithmetic identity could prove are shown. A blank cell means the figure
could not be proven, not that it is zero. Screening excludes companies with no proven
value for the metric being screened, and says how many it excluded.

Every company page links the audited PDFs its figures were read from, so any number can
be checked against the page it came from.

## Build

The page is a single self-contained HTML file, generated — not hand-edited.

```
cd scraper
python revalidate.py              # re-score every document
python build_dataset.py           # company-year rows, ratios, derivations
python build_screener_payload.py  # one row per company + per-year records
python build_screener_page.py     # inject into screener_template.html
```

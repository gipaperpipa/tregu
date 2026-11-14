# Tregu

Kosovo's private economy, as it moves: business formation and closure for every
registered business, monthly since 2001, from the ARBK business registry — and
fundamentals for the larger companies, read from audited financial statements published
by the Ministry of Finance (mf.rks-gov.net).

*Tregu* is Albanian for **the market**.

These are private companies: no share price or market cap exists. This is a fundamentals
screener, not an exchange.

## What it shows

- **Pulse** (the home page) — new businesses and closures by month, sector and
  municipality; who is starting them; and the Tregu Index, revenue growth of the same
  audited companies year on year, chained, so a change in *who filed* is never read as a
  change in the economy
- **Sector and municipality pages** — formation, what is being started and where, who
  is starting it, and the audited companies there with their own like-for-like index
- **Watchlist** — follow a company, sector or municipality; Tregu marks what is new when
  you come back (kept in your browser only)
- **893 companies**, 660 matched to the business registry, spanning fiscal years 2013–2025
- **Screener** — each company at its own best-covered recent year
- **By fiscal year** — every company on one chosen year, so no two rows are years apart
- **Sector league table**, **Movers**, and **Data quality**

## The one rule

Only figures an arithmetic identity could prove are shown. A blank cell means the figure
could not be proven, not that it is zero. Screening excludes companies with no proven
value for the metric being screened, and says how many it excluded.

Published figures are audited against their pages: the latest audit found **48 of 50** randomly drawn figures exactly as printed, and both causes of the misses are fixed. See [AUDIT.md](AUDIT.md) for every figure checked, each linked to its page.

Every company page links the audited PDFs its figures were read from, so any number can
be checked against the page it came from.

## Build

The page is a single self-contained HTML file, generated — not hand-edited.

```
cd scraper
python revalidate.py              # re-score every document
python build_dataset.py           # company-year rows, ratios, derivations
python build_screener_payload.py  # one row per company + per-year records
python build_pulse.py             # registry series for the Pulse (needs the warehouse)
python build_screener_page.py     # inject into screener_template.html
```

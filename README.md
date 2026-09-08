# Idaho Donor Map

A tool for looking up an Idaho political candidate and seeing patterns in who funds them, career donor percentage, party lean of their donor pool, PAC versus individual giving, and more.

## Why This Exists

A donor list on its own is just names. The patterns in it, who repeats, who clusters around which candidates, are what actually matter, and seeing those patterns requires clean, structured data and the right calculations run against it. This project is the public-facing tool built on top of that structured data.

## Status

Early planning and data discovery. The current focus is understanding the shape of Idaho's live campaign finance API (2023–present) well enough to build an accurate data model before any pipeline or public tool is built.

## Related Project

This project uses data sourced and standardized in [idaho-campaign-finance-data](https://github.com/RollForData/idaho-campaign-finance-data), which handles pulling and reconciling Idaho's campaign finance records. This repo is the scorecard tool built on top of that work.

## Repo Structure

    idaho-donor-map/
    ├── README.md
    ├── docs/
    │   ├── erd.md
    │   ├── metrics.md
    │   └── api/
    │       └── readme.md
    │       └── endpoints/
    │           ├── candidates.md
    │           ├── committees.md
    │           ├── contributions.md
    │           └── loans.md
    └── scripts/
        └── pull_data.py

## Built By

RollForData
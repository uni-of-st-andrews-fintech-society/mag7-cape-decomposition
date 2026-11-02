# data/

Download scripts, one per source (yfinance, SEC EDGAR, FRED, Shiller, and WRDS if available). Each script saves its output to `data/raw/`.

`data/raw/` is gitignored, so licensed or raw data is never committed. Rerun the scripts to rebuild it.

The frozen dataset is tagged (e.g. `data-v1`), and the tag is recorded in `logs/decisions.md`.

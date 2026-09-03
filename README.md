# EUSTX50 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_836_357_rows-blue)](https://getdata.finance/datasets/eustx50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eustx50)

### -> [**Download the full EUSTX50 dataset on getdata.finance**](https://getdata.finance/datasets/eustx50)

**EUSTX50 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **EURO STOXX 50**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **EURO STOXX 50** (Index)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eustx50) · **2,836,357** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `EUSTX50_1m.csv` (55,440 rows, `2026-06-01` -> `2026-09-01`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eustx50)** — **2,836,357** `1m` rows, **11 timeframes**, `2012-08-27` -> `2026-09-01`.

## Download sample

**[EUSTX50_1m.csv](https://github.com/getdata-finance/eustx50-1m-ohlcv-index-historical-data/blob/main/EUSTX50_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eustx50-1m-ohlcv-index-historical-data/main/EUSTX50_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eustx50))** |
|---|--:|---|
| Instrument | EURO STOXX 50 · Index | EURO STOXX 50 · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **2,836,357** |
| Period | `2026-06-01` -> `2026-09-01` | `2012-08-27` -> `2026-09-01` |
| File | `EUSTX50_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Coverage report | — | [EUSTX50 coverage](https://getdata.finance/coverage/eustx50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eustx50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-06-01T19:55:00+00:00 | 6123.52 | 6123.52 | 6121.51 | 6121.51 | 25 |
| 2026-06-01T19:56:00+00:00 | 6121.51 | 6121.52 | 6119.5 | 6121.51 | 25 |
| 2026-06-01T19:57:00+00:00 | 6121.51 | 6121.51 | 6121 | 6121 | 3 |
| 2026-06-01T19:58:00+00:00 | 6121 | 6121.52 | 6120.01 | 6120.5 | 16 |
| 2026-06-01T19:59:00+00:00 | 6120.5 | 6122.5 | 6120.5 | 6121.06 | 42 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 6343.94 | 6345.44 | 6343.93 | 6344.94 | 27 |
| 2026-09-01T19:56:00+00:00 | 6344.94 | 6344.94 | 6344.42 | 6344.94 | 3 |
| 2026-09-01T19:57:00+00:00 | 6344.94 | 6345.93 | 6343.93 | 6343.93 | 18 |
| 2026-09-01T19:58:00+00:00 | 6343.93 | 6345.43 | 6343.93 | 6345.43 | 6 |
| 2026-09-01T19:59:00+00:00 | 6345.43 | 6345.43 | 6343.42 | 6343.47 | 34 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full EUSTX50 archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full EUSTX50 dataset on getdata.finance](https://getdata.finance/datasets/eustx50)**

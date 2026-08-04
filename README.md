# EUSTX50 1m OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_747_479_rows-blue)](https://getdata.finance/datasets/eustx50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eustx50)

### -> [**Download the full EUSTX50 dataset on getdata.finance**](https://getdata.finance/datasets/eustx50)

**EUSTX50 1m OHLCV stock index historical data** — ultra high-quality 1m OHLCV for **Euro Stoxx 50**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Euro Stoxx 50** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eustx50) · **2,747,479** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `EUSTX50_1m.csv` (106,679 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/eustx50)** — **2,747,479** `1m` rows (~191.47 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `2012-08-27` -> `2026-07-30`.

## Download sample

**[EUSTX50_1m.csv](https://github.com/getdata-finance/eustx50-1m-ohlcv-index-historical-data/blob/main/EUSTX50_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eustx50-1m-ohlcv-index-historical-data/main/EUSTX50_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/eustx50-1m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eustx50-1m-ohlcv-index-historical-data/](https://getdata-finance.github.io/eustx50-1m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eustx50](https://getdata.finance/datasets/eustx50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eustx50))** |
|---|--:|---|
| Instrument | Euro Stoxx 50 · Stock index | Euro Stoxx 50 · Stock index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 106,679 | **2,747,479** |
| Size | 9.15 MB | ~191.47 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2012-08-27` -> `2026-07-30` |
| File | `EUSTX50_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Coverage report | — | [EUSTX50 coverage](https://getdata.finance/coverage/eustx50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eustx50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/eustx50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T07:00:00+00:00 | 5937.31 | 5941.81 | 5935.81 | 5940.81 | 59.8699853587 |
| 2026-02-02T07:01:00+00:00 | 5940.81 | 5940.81 | 5878.59 | 5884.58 | 35 |
| 2026-02-02T07:02:00+00:00 | 5884.58 | 5885.58 | 5879.57 | 5880.58 | 31 |
| 2026-02-02T07:03:00+00:00 | 5880.58 | 5882.08 | 5878.57 | 5881.09 | 21 |
| 2026-02-02T07:04:00+00:00 | 5881.09 | 5881.57 | 5878.57 | 5879.57 | 28 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T19:55:00+00:00 | 6484.66 | 6484.66 | 6477.67 | 6477.67 | 20 |
| 2026-07-31T19:56:00+00:00 | 6477.67 | 6477.67 | 6477.17 | 6477.17 | 3 |
| 2026-07-31T19:57:00+00:00 | 6477.17 | 6477.17 | 6472.65 | 6472.65 | 70 |
| 2026-07-31T19:58:00+00:00 | 6472.65 | 6473.17 | 6470.65 | 6470.67 | 76 |
| 2026-07-31T19:59:00+00:00 | 6470.67 | 6470.67 | 6467.15 | 6469.2 | 54 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EUSTX50_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EUSTX50_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('EUSTX50_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **EUSTX50** archive on **[getdata.finance](https://getdata.finance/datasets/eustx50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,747,479** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full EUSTX50 dataset on getdata.finance](https://getdata.finance/datasets/eustx50)**

---
*GetData · EUSTX50 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eustx50) · 2026-08-04 UTC*

# TSLA 3m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-205_704_rows-blue)](https://getdata.finance/datasets/tsla) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/tsla)

### -> [**Download the full TSLA dataset on getdata.finance**](https://getdata.finance/datasets/tsla)

**TSLA 3m OHLCV stocks historical data** — ultra high-quality 3m OHLCV for **Tesla**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **Tesla** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/tsla) · **205,704** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `TSLA_3m.csv` (18,480 rows, `2026-02-06` -> `2026-09-01`, 1.91 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/tsla)** — **205,704** `3m` rows (full `1m`: 617,080), **11 timeframes**, `2020-02-25` -> `2026-09-01`.

## Download sample

**[TSLA_3m.csv](https://github.com/getdata-finance/tsla-3m-ohlcv-stocks-historical-data/blob/main/TSLA_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/tsla-3m-ohlcv-stocks-historical-data/main/TSLA_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/tsla-3m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/tsla-3m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/tsla-3m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/tsla](https://getdata.finance/datasets/tsla)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/tsla))** |
|---|--:|---|
| Instrument | Tesla · US stocks | Tesla · US stocks |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 18,480 | **205,704** |
| Size | 1.91 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/tsla) |
| Period | `2026-02-06` -> `2026-09-01` | `2020-02-25` -> `2026-09-01` |
| File | `TSLA_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/tsla) |
| Coverage report | — | [TSLA coverage](https://getdata.finance/coverage/tsla) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/tsla)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/tsla) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`TSLA_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 409.61 | 409.61 | 408.92 | 409.02 | 495 |
| 2026-02-06T20:03:00+00:00 | 409.02 | 409.5 | 408.9 | 409.49 | 428 |
| 2026-02-06T20:06:00+00:00 | 409.49 | 409.56 | 408.86 | 408.95 | 391 |
| 2026-02-06T20:09:00+00:00 | 408.95 | 409.47 | 408.76 | 409.33 | 469 |
| 2026-02-06T20:12:00+00:00 | 409.33 | 409.98 | 409.22 | 409.86 | 395 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:45:00+00:00 | 355.34 | 355.67 | 355.18 | 355.53 | 318 |
| 2026-09-01T19:48:00+00:00 | 355.53 | 355.55 | 354.66 | 355.05 | 369 |
| 2026-09-01T19:51:00+00:00 | 355.05 | 355.48 | 354.55 | 355.25 | 386 |
| 2026-09-01T19:54:00+00:00 | 355.25 | 355.47 | 354.65 | 355.14 | 450 |
| 2026-09-01T19:57:00+00:00 | 355.14 | 355.26 | 354.8 | 355.26 | 583 |

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

df = pd.read_csv('TSLA_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('TSLA_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('TSLA_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **TSLA** archive on **[getdata.finance](https://getdata.finance/datasets/tsla)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **205,704** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full TSLA dataset on getdata.finance](https://getdata.finance/datasets/tsla)**

---
*GetData · TSLA 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/tsla)*

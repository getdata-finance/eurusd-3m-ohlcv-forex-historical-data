# EURUSD 3m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-570_409_rows-blue)](https://getdata.finance/datasets/eurusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eurusd)

### -> [**Download the full EURUSD dataset on getdata.finance**](https://getdata.finance/datasets/eurusd)

**EURUSD 3m OHLCV forex historical data** — ultra high-quality 3m OHLCV for **Euro / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **Euro / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eurusd) · **570,409** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `EURUSD_3m.csv` (63,238 rows, `2026-03-26` -> `2026-09-25`, 5.87 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eurusd)** — **570,409** `3m` rows (full `1m`: 1,685,501), **11 timeframes**, `2022-02-27` -> `2026-09-25`.

## Download sample

**[EURUSD_3m.csv](https://github.com/getdata-finance/eurusd-3m-ohlcv-forex-historical-data/blob/main/EURUSD_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eurusd-3m-ohlcv-forex-historical-data/main/EURUSD_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/eurusd-3m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eurusd-3m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/eurusd-3m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eurusd](https://getdata.finance/datasets/eurusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eurusd))** |
|---|--:|---|
| Instrument | Euro / US Dollar · Forex | Euro / US Dollar · Forex |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 63,238 | **570,409** |
| Size | 5.87 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eurusd) |
| Period | `2026-03-26` -> `2026-09-25` | `2022-02-27` -> `2026-09-25` |
| File | `EURUSD_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eurusd) |
| Coverage report | — | [EURUSD coverage](https://getdata.finance/coverage/eurusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eurusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/eurusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURUSD_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:30:00+00:00 | 1.16637 | 1.16638 | 1.16608 | 1.16609 | 216 |
| 2026-03-26T02:33:00+00:00 | 1.16609 | 1.16612 | 1.16584 | 1.16585 | 325 |
| 2026-03-26T02:36:00+00:00 | 1.16585 | 1.16591 | 1.16555 | 1.16566 | 302 |
| 2026-03-26T02:39:00+00:00 | 1.16566 | 1.16592 | 1.1656 | 1.16591 | 239 |
| 2026-03-26T02:42:00+00:00 | 1.16591 | 1.166 | 1.16586 | 1.16591 | 200 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T20:45:00+00:00 | 1.13932 | 1.13934 | 1.13926 | 1.1393 | 255 |
| 2026-09-25T20:48:00+00:00 | 1.1393 | 1.13934 | 1.13917 | 1.13924 | 182 |
| 2026-09-25T20:51:00+00:00 | 1.13924 | 1.13925 | 1.13919 | 1.13919 | 116 |
| 2026-09-25T20:54:00+00:00 | 1.13919 | 1.13925 | 1.13901 | 1.13904 | 327 |
| 2026-09-25T20:57:00+00:00 | 1.13904 | 1.13913 | 1.13899 | 1.13902 | 408 |

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

df = pd.read_csv('EURUSD_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURUSD_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EURUSD_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **EURUSD** archive on **[getdata.finance](https://getdata.finance/datasets/eurusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **570,409** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full EURUSD dataset on getdata.finance](https://getdata.finance/datasets/eurusd)**

---
*GetData · EURUSD 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eurusd)*

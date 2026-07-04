# USDCNH 1h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_696_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full USDCNH dataset on ork.ad**](https://ork.ad/)

**USDCNH 1h OHLCV Forex historical data** — ultra high-quality 1h OHLCV for **US Dollar / Chinese Yuan**. 24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **US Dollar / Chinese Yuan** (Forex)
- **24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **4,696** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `USDCNH_1h.csv` (4,552 rows, `2025-10-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **4,696** `1h` rows (~0.3 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-09-24` → `2026-07-02`.

## Download sample

**[USDCNH_1h.csv](https://github.com/ork-ad/usdcnh-1h-ohlcv-forex-historical-data/blob/main/USDCNH_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/usdcnh-1h-ohlcv-forex-historical-data/main/USDCNH_1h.csv)) · [GitHub Releases](https://github.com/ork-ad/usdcnh-1h-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/usdcnh-1h-ohlcv-forex-historical-data/](https://ork-ad.github.io/usdcnh-1h-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | US Dollar / Chinese Yuan · Forex | US Dollar / Chinese Yuan · Forex |
| Timeframes | `1h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1h rows | 4,552 | **4,696** |
| Size | 0.29 MB | ~0.3 MB |
| Period | `2025-10-02` → `2026-07-02` | `2025-09-24` → `2026-07-02` |
| File | `USDCNH_1h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDCNH_1h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-02T22:00:00Z | 7.130721 | 7.134831 | 7.129531 | 7.133721 | 3596.0 |
| 2025-10-02T23:00:00Z | 7.133721 | 7.134321 | 7.129822594312969 | 7.132031 | 2319.0 |
| 2025-10-03T00:00:00Z | 7.132031 | 7.13467 | 7.132011 | 7.134451 | 4843.0 |
| 2025-10-03T01:00:00Z | 7.134451 | 7.13697 | 7.133301 | 7.134831 | 5550.0 |
| 2025-10-03T02:00:00Z | 7.134831 | 7.137981 | 7.134772693313464 | 7.137121 | 4064.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T18:00:00Z | 6.78908 | 6.78918 | 6.78675 | 6.78714 | 4865.0 |
| 2026-07-02T19:00:00Z | 6.78714 | 6.78884 | 6.7871 | 6.78755 | 5294.0 |
| 2026-07-02T20:00:00Z | 6.78755 | 6.78847 | 6.78683 | 6.78844 | 1230.0 |
| 2026-07-02T21:00:00Z | 6.78844 | 6.78844 | 6.78327 | 6.78423 | 2654.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDCNH_1h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDCNH_1h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('USDCNH_1h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **USDCNH** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **4,696** rows at `1h`, plus all other timeframes in the same ZIP.

**[→ Get the full USDCNH dataset on ork.ad](https://ork.ad/)**

---
*GetData · USDCNH 1h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*
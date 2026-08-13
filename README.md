# Multi-Pair RSI Alert Scanner (MT4)

MetaTrader 4 multi-pair **RSI scanner** that monitors selected symbols across H1 / M15 / M1, detects aligned RSI crosses, and sends push/panel alerts **without placing trades**.

---

## What This Tool Is For

Use this scanner when you want to:

- Watch multiple pairs from one MT4 chart
- Confirm H1 + M15 RSI bias before acting on an M1 cross
- Receive one clean alert per valid signal (no duplicate spam)
- Keep a live RSI status panel on the chart

---

## How It Works

```text
Enabled symbols
        ↓
H1 + M15 RSI bias
        ↓
M1 RSI threshold cross (closed candle)
        ↓
Aligned BUY / SELL alert + panel update
```

1. Resolves broker symbols for each enabled pair.
2. Reads RSI on H1, M15, and M1.
3. Detects M1 crosses of the RSI threshold.
4. Requires matching H1/M15 bias before alerting.
5. Updates the on-chart panel with live RSI values and last signal.

---

## Key Features

- Multi-pair scanning
- H1 / M15 / M1 confluence rules
- Push-friendly alert messages
- On-chart dashboard panel
- Non-trading scanner

---

## Technologies Used

- MetaTrader 4 / MQL4

## Supported Platforms

- MetaTrader 4

---

## Main Files

| File | Role |
|---|---|
| `RSI_Scanner.mq4` | Scanner source |

---

## Important Notes

- Does not place trades.
- No profitability claims.

## Limitations

- Depends on MT4 notification configuration and symbol name mapping.

---

## Contact

**WhatsApp:** +923147121270

**Email:** [kaleemullahkhan.contact@gmail.com](mailto:kaleemullahkhan.contact@gmail.com)

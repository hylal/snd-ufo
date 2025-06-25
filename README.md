# snd-ufo
# 📊 SnD-UFO Indicator (Supply & Demand + Unfilled Orders)

Pine Script v5 TradingView indicator to detect **RBR (Rally-Base-Rally)** and **DBD (Drop-Base-Drop)** patterns using smart Supply & Demand logic combined with body health analysis and multi-timeframe EMA support.

---

## 🔍 Features

- ✅ Auto-detect **Bullish RBR** and **Bearish DBD** patterns  
- ✅ Supply & Demand zone marking with conditional filters  
- ✅ Multi-timeframe EMA plotting (Weekly, Daily, 4H, 1H)  
- ✅ Built-in EMA 20 / 50 / 100 / 200 on current timeframe  
- ✅ Candle body health check to validate base  
- ✅ Alert conditions for all and first pattern appearances  
- ✅ Configurable base retracement tolerance and candle health  
- ✅ No repaint (fully confirmed structure)

---
## $$ PAIRS
EURUSD  
GBPUSD  
AUDUSD  
NZDUSD  
USDJPY  
USDCHF  
USDCAD  
EURGBP  
EURJPY  
EURCHF  
EURCAD  
EURAUD  
EURNZD  
GBPJPY  
GBPCHF  
GBPCAD  
GBPAUD  
GBPNZD  
AUDJPY  
AUDCHF  
AUDCAD  
AUDNZD  
NZDJPY  
NZDCHF  
NZDCAD  
CADJPY  
CADCHF  
CHFJPY  


## ⚙️ Input Settings

| Parameter Name         | Description                              | Default |
|------------------------|------------------------------------------|---------|
| Candle Health %        | Minimum % of healthy body structure      | 70      |
| Base Max Retracement   | Max retracement allowed in base candle   | 0.80    |
| Multi-Timeframe EMA    | EMA period for MTF trend direction       | 9       |

---

## 🧠 Pattern Logic

### Bullish: RBR (Rally-Base-Rally)
- Triggered after strong bullish candle > previous high  
- Valid base = bearish candle with small body  
- Entry zone = between bull low and retracement base  
- Confirmed with breakout and retracement condition

### Bearish: DBD (Drop-Base-Drop)
- Triggered after strong bearish candle < previous low  
- Valid base = bullish candle with small body  
- Entry zone = between bear high and retracement base  
- Confirmed with breakdown and retracement condition

---

## 📉 EMA Plots

- EMA Weekly (Blue)  
- EMA Daily (Orange)  
- EMA 4H (Purple)  
- EMA 1H (Green)  
- EMA 20/50/100/200 (Current TF, standard colors)

---

## 🔔 Alerts

| Alert Name              | Trigger                                  |
|-------------------------|-------------------------------------------|
| All Bullish Pattern     | Any RBR zone formed                       |
| All Bearish Pattern     | Any DBD zone formed                       |
| First Bullish Pattern   | First RBR after bearish pattern           |
| First Bearish Pattern   | First DBD after bullish pattern           |

---

## 📜 License

This indicator is licensed under the [Mozilla Public License 2.0](https://www.mozilla.org/MPL/2.0/).

---

## ✍️ Author

**Hilaludin Wahid**  
🔗 [LinkedIn]([#](https://www.linkedin.com/in/hilaludinwahid/)) | 🌐 [hilal.wahanadigita.com](https://hilal.wahanadigita.com)

---

## 💡 Notes

- Works best on trending markets and volatile sessions.  
- Always combine with market structure and HTF confluence.

---

## 📦 Installation

1. Copy the source code into [TradingView Pine Editor](https://www.tradingview.com/pine-script-docs/en/v5/).
2. Save and add to chart.
3. Adjust settings as needed.


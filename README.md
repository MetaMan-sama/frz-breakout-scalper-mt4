# FRZ Breakout Scalper Free — MT4 Expert Advisor

A third-party MetaTrader 4 **Expert Advisor (EA)** distributed in compiled `.ex4` binary format that implements a **breakout scalping strategy** — entering trades on confirmed price breakouts from defined consolidation or range structures, targeting short-duration high-probability momentum moves with tight risk management.

---

## Overview

The FRZ Breakout Scalper is a pre-compiled EA designed for scalping breakout setups — a high-frequency trading approach that seeks to capture the rapid directional price expansion that occurs when price breaks beyond a period of consolidation or a defined structural level. Breakout scalping strategies typically operate on short timeframes (M1–M15), use small lot sizes with tight stop losses, and exit trades quickly to lock in momentum-driven gains before the move exhausts itself. This file is the **Free version (v5)** of the EA, which typically includes the core breakout detection and entry logic with limited configuration options compared to paid versions.

> **Source code not available.** This EA is distributed as a compiled `.ex4` binary only. The source `.mq4` file is not included in this repository. Behavior documented here is based on the filename, version label, and general breakout scalper EA conventions.

---

## File Information

| Property        | Value                                       |
|-----------------|---------------------------------------------|
| File            | `FRZ_Breakout_Scalper_Free_MT4_v5.ex4`      |
| Type            | MetaTrader 4 Expert Advisor (compiled binary)|
| Version         | v5 (Free edition)                           |
| Source available| No — binary only                            |

---

## Installation

1. Copy `FRZ_Breakout_Scalper_Free_MT4_v5.ex4` to the MetaTrader 4 **Experts** folder:
   ```
   MQL4/Experts/
   ```
2. Restart MetaTrader 4 or right-click the Navigator panel and select **Refresh**
3. Locate the EA under **Navigator → Expert Advisors**
4. Drag onto a chart; configure parameters in the dialog and click **OK**
5. Ensure **AutoTrading** is enabled in the MT4 toolbar

> **Warning:** This EA places real trades. Always test on a **demo account** first before deploying on live capital. Compiled EAs cannot be inspected for source code — verify the EA's behavior on demo before trusting it with real funds.

> **Note:** `.ex4` files are tied to the MetaTrader 4 build they were compiled against. If the EA fails to load, ensure your MT4 terminal is up to date.

---

## Requirements

- MetaTrader 4 (compatible build)
- AutoTrading enabled in MT4 toolbar
- Demo account strongly recommended before live use

---

## License

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

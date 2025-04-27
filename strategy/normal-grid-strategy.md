# Normal Grid Strategy

### Goal

Capture small, repeatable profits by trading price fluctuations within a defined range.

***

### How It Works

The Normal Grid Strategy divides a chosen price range into evenly spaced levels — like rungs on a ladder.

* **Buy orders** are placed at regular intervals below the current market price.
* **Sell orders** are placed at regular intervals above it.

As the market moves:

* A drop triggers a buy at a lower level.
* A rise triggers a sell at a higher level.

Each completed buy-sell cycle locks in a small profit, aiming to accumulate gains over time without needing to predict market direction.

Your USDT deposit is automatically split across the grid to size orders proportionally.

***

### Key Mechanism

* **Equal Spacing**:\
  Grid levels are evenly distributed between a user-defined upper and lower price boundary.
* **Passive Execution**:\
  Once set, the strategy runs without needing manual intervention — orders are maintained automatically as prices move.
* **Profit Source**:\
  Profits come from capturing the difference between buy and sell grid levels, minus trading fees.

***

### Risks to Know

* **Requires Sideways or Range-Bound Markets**:\
  If the market moves sharply and breaks outside the grid range, open positions may become stranded.
* **Exposure Risk**:\
  If price falls below the lowest grid level (or rises above the highest) without reversal, you can end up holding assets at a loss.
* **Trading Fees Erode Margins**:\
  Each buy and sell incurs exchange fees — small profits can be wiped out if grids are set too tight or volume is too low.
* **Manual Adjustment May Be Needed**:\
  If volatility shifts significantly, you might need to manually reset the grid range to continue being effective.

***

### Best Use Scenarios

Normal Grid Strategy is useful when you believe a token will trade **sideways** or within a known range for a while.\
It is **not** designed for trending or breakout markets.

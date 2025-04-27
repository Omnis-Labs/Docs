# Aster Points Maximizer

### Goal

Maximize AsterDEX trading rewards by generating continuous, high-frequency trading volume.

***

### How It Works

The Aster Points Maximizer uses your deposited USDT to perform a rapid sequence of market buy and sell orders.\
Each cycle:

* It buys an asset at market price.
* It immediately sells it back at market price.

This generates trading volume, which accumulates AsterDEX reward points over time.\
The system automatically sizes orders based on your USDT balance, optimizing for maximum eligible volume while minimizing errors.

***

### Key Mechanism

* **Buy and Sell Loops**:\
  Each iteration involves a full market buy followed by a market sell of the same asset.
* **Order Sizing**:\
  USDT deposit amount determines the order size per trade, ensuring trades meet minimum exchange notional values without excessive slippage.
* **Cycle Control**:\
  You can configure how many buy/sell cycles you want the vault to perform, balancing point generation against cost.

***

### Risks to Know

* **Designed for points, not profit**:\
  This strategy is intentionally inefficient in terms of trading profitability.
* **Trading fees and slippage add up**:\
  Every buy and sell incurs small fees and possible minor slippage. Over time, these costs can erode your USDT balance.
* **Aggressive use can lead to noticeable losses**:\
  Running many cycles without monitoring will cause capital decay.
* **Execution is exchange-dependent**:\
  Outages or anomalies on AsterDEX could disrupt trade execution.

***

### Best Use Scenarios

Use the Aster Points Maximizer **only** when your goal is clear:\
**You are willing to accept a controlled loss in order to maximize AsterDEX reward points or qualify for incentive programs.**

Not recommended for users seeking profit from trading itself.

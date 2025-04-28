# Architecture Overview

Omnis is built as a modular, AI-driven platform designed for dynamic DeFi portfolio management and real-time risk control.

At a high level, the system combines:

* **Omnis Edge** — Prebuilt on-chain strategy vaults for different risk levels.
* **Omnis One** — An AI-managed portfolio builder that dynamically allocates across multiple strategies based on user preferences and market conditions.
* **Omnis AI Lab** — Our internal AI research engine powering dynamic parameter optimization, generative strategy creation, and continuous learning.

For the full technical breakdown — including mathematical models, AI reinforcement learning flows, GenAI-based strategy generation, and smart contract infrastructure — **read the Omnis Litepaper** [**here**](https://drive.google.com/file/d/1ItjHhR_KYrBKJDWAGnY98bkY2GTH6FDR/view?usp=sharing).

***

### Key Design Principles

#### 1. Modular Strategy Infrastructure

Omnis is split into two product layers:

* **Edge Vaults**: Pre-tested strategies, optimized for different market conditions (momentum, mean reversion, liquidity farming, etc.).
* **One Vaults**: Fully customizable AI-managed portfolios that combine multiple strategies, dynamically adjusted using real-time on-chain signals.

This separation makes the system flexible — allowing users to either plug into ready-made strategies or configure custom allocations.

***

#### 2. Multi-Agent AI System

Omnis AI Lab coordinates three types of AI agents:

* **Strategy Generation AI**:\
  Uses GenAI to create, test, and deploy new strategy vaults automatically based on user goals.
* **Position Management AI**:\
  Dynamically tunes leverage, position sizing, and risk thresholds using reinforcement learning.
* **Transactional AI Assistant**:\
  Optimizes trade execution, detects arbitrage opportunities, and adapts liquidity provision in real-time.

These agents work together to constantly adapt to changing DeFi markets — not just running fixed strategies.

***

#### 3. On-Chain Transparency & Execution

All Omnis strategies are deployed on-chain (starting with BSC, expanding multi-chain), using:

* Smart contract vaults visible and auditable by anyone.
* Direct decentralized execution on DEXs like AsterDEX — without relying on centralized custody.

***

👉 **Want to dive deeper?**\
Read the full Omnis Litepaper [here](https://drive.google.com/file/d/1ItjHhR_KYrBKJDWAGnY98bkY2GTH6FDR/view?usp=sharing).

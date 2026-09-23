# SeReborn Gold - Official EA License & Verification Server

Welcome to the official repository for **SeReborn Gold**, a precision automated algorithmic trading system engineered for **XAUUSD (GOLD)** on the **MetaTrader 5 (MT5)** platform.

---

## 🚨 MANDATORY REQUIREMENT: CENT ACCOUNT ONLY
> **WARNING:** This EA is strictly designed and calibrated for **CENT ACCOUNTS (Pro-Cent)** only.
> **DO NOT RUN THIS EA ON A STANDARD USD ACCOUNT.**
> 
> **Why Cent Account Only?**
> The EA employs a multi-step recovery sequence starting from a base volume of `0.01 lot`. On a standard USD account, Gold pip fluctuations and larger recovery steps require massive equity to survive extended market swings. A Cent account converts small capital (e.g., $200 USD into 20,000 cents), providing the necessary buffer, leverage, and margin cushion for the strategy to execute safely without risk of margin call.

---

## ⚡ System Highlights
- **100% Single Entry:** No grid, no layering, and no dangerous averaging. Only one active position at any given time.
- **Smart Auto-Recovery Mechanism:** Automated recovery cycle designed to safely recover drawdown without loading account margin.
- **Stealth Execution:** Real TP & SL targets are executed internally to prevent broker stop-hunting.
- **Swap-Free Ready:** Zero overnight fee impact on holding positions over consecutive days.
- **Disciplined Intraday Timing:** Active trading during high-liquidity market sessions only.

---

## 🏛️ Official Supported Broker
This Expert Advisor is optimized and officially supported for:
- **RoboForex** (Pro-Cent / Swap-Free / Islamic)

---

## 🚀 How to Get & Activate SeReborn Gold EA

Follow these simple steps to activate the EA for your account:

### Step 1: Register Under the Official Partner Link
Create your RoboForex trading account using the official link below:
- **RoboForex Registration:** [Click Here to Register](https://my.roboforex.com/en/?a=ysoc)  
  *(Partner Code: `ysoc`)*

### Step 2: Open an MT5 Pro-Cent Trading Account
- **Platform:** MetaTrader 5 (MT5)
- **Account Type:** **Pro-Cent** (Mandatory — Cent account only)
- **Currency:** USC (US Cent)
- **Account Mode:** Swap-Free (Islamic recommended)
- **Recommended Deposit:** 20,000 Cent ($200 USD base capital)
- **Leverage:** 1:500 or higher

### Step 3: Request EA Activation
Send your MT5 Pro-Cent account number directly to the developer for verification:
- **Telegram Support:** [@au5513](https://t.me/au5513)

Once verified, your account number will be added to this repository's whitelist (`accounts.txt`), and the official EA file (`SeReborn.ex5`) will be sent directly to your Telegram.

---

## ⚙️ Quick Installation Guide (MT5)

1. **Enable WebRequest in MT5 (Crucial):**
   - In MT5, navigate to: `Tools` ➔ `Options` ➔ `Expert Advisors` tab.
   - Check **"Allow WebRequest for listed URL"**.
   - Add the following URL into the whitelist box:
     ```text
     [https://raw.githubusercontent.com](https://raw.githubusercontent.com)
     ```
2. **Install EA File:**
   - Copy the received `SeReborn.ex5` into your MT5 `MQL5/Experts/` folder.
   - Restart MT5 or right-click **Experts** in the Navigator window and click **Refresh**.
3. **Attach to Chart:**
   - Open **XAUUSD / GOLD** on the **M15** timeframe.
   - Attach **SeReborn Gold** to the chart and ensure **Algo Trading** is enabled.

---

## ⚠️ Risk Disclaimer
*Trading foreign exchange and commodities on margin carries a high level of risk and may not be suitable for all investors. Past performance is no guarantee of future results. Always practice proper money management and trade with capital you can afford to risk.*

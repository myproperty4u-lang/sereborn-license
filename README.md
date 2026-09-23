# SeReborn Gold - Official EA License & Verification Server

Welcome to the official repository for **SeReborn Gold**, a precision automated algorithmic trading system engineered for **XAUUSD (GOLD)** on the **MetaTrader 5 (MT5)** platform.

---

## 🚨 MANDATORY REQUIREMENT: CENT ACCOUNT ONLY
> **WARNING:** This EA is strictly designed and calibrated for **CENT ACCOUNTS (Pro-Cent)** only.
> **DO NOT RUN THIS EA ON A STANDARD USD ACCOUNT.**
> 
> **Why Cent Account Only?**
> The EA utilizes an automated recovery cycle starting from a base volume of `0.01 lot`. On a standard USD account, Gold pip values and progressive recovery steps require massive equity to withstand market volatility. A Cent account converts small capital (e.g., $200 USD into 20,000 cents), providing the necessary margin cushion and leverage buffer for the strategy to execute safely without risk of a margin call.

---

## 📈 Trading Strategy & Operational Logic

SeReborn Gold operates on an institutional-grade, disciplined trading framework designed specifically for the unique volatility of Gold:

1. **100% Single-Entry Discipline (Zero Grid / No Averaging):**
   - The EA never stacks, averages down, or opens multiple simultaneous trades.
   - It maintains strictly **ONE active position at any given time**, ensuring margin levels remain healthy and eliminating prolonged catastrophic floating drawdowns.

2. **Trend Momentum Follow-Through:**
   - Every time a position hits its **Take Profit (TP)** target, the algorithm acknowledges market direction and immediately re-enters in the same trend direction using the minimum baseline volume (`0.01 lot`).

3. **Smart Reverse Recovery Mechanism:**
   - If an entry hits a **Stop Loss (SL)** due to sudden market shifts or false breakouts, the EA instantly initiates an intelligent counter-trend reversal.
   - It activates an automated, non-linear progressive lot recovery sequence designed to clear the entire preceding loss series with a single successful TP touch, resetting the cycle cleanly back to baseline.

4. **Stealth Target Execution (Anti Stop-Hunt):**
   - The EA sends wide decoy stop and profit levels to the broker server while maintaining tight, precise internal stealth exits (`Real TP: 400 pips / Real SL: 300 pips`), shielding your execution targets from broker stop-hunting and spread widenings.

5. **Disciplined Intraday Session Management:**
   - Trading is synchronized strictly with high-liquidity market hours to avoid erratic overnight spreads and low-volume consolidation traps.

---

## ⚡ System Highlights
- **Pair:** XAUUSD (Gold)
- **Timeframe:** M15
- **Style:** Disciplined Intraday / Single Entry
- **Swap-Free Ready:** Zero overnight holding cost penalty
- **Integrated Dashboard:** Real-time HUD tracking live spread, floating PnL, margin levels, and daily/weekly/monthly profit telemetry

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

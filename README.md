# 📈 Reliance Mean Reversion Automated Trade Strategy  

## 📌 Overview  
This repository contains an **automated trading strategy** for **Reliance Industries (RELIANCE.NS)** based on **mean reversion principles**.  
The strategy identifies **overbought and oversold conditions** using **RSI, MACD, Bollinger Bands, and Moving Averages** to execute **buy and sell trades automatically**.

---

## ⚡ Features  
- ✅ **Mean Reversion Based Strategy** 📉📈  
- ✅ Uses **RSI, MACD, Bollinger Bands, and Moving Averages** for confirmation  
- ✅ **Automated Entry & Exit Detection** 🚀  
- ✅ **Backtesting & PnL Calculation** 💰  
- ✅ Supports **stop-loss & risk management**  

---

## 📊 Strategy Logic  

### 📥 **Entry Conditions** (Buying)  
A **long trade** is entered when:  
- **RSI ≥ 50** (momentum turning bullish)  
- **MACD Histogram increasing** (bullish trend confirmation)  
- **Price forming a higher high**  
- **Close above Support**  
- **Price above 20-MA but below 100-MA** (pullback opportunity)  
- **Volume increasing**  

### 📤 **Exit Conditions** (Selling)  
A **long position** is exited when:  
- Stop-loss is hit  
- Price faces **rejection at resistance** or **100-MA**  
- **High-volume red candles appear**  
- Price fails to hold above **20-MA or Support**  

Similar logic applies for **short trades** (reverse conditions).  

---


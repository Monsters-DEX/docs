# 💰 Fees

## Introduction

In line with industry standard, **trade** **fees are calculated on the value of the total position size** (collateral x leverage). **Borrowing and overnight Interest** **fees are calculated on the borrowed value of the total position size**.

### Cryptocurrencies

1. **Opening a trade: 0.07%**
   * 0.05% -> Ecosystem
     * 0.014-0.02% -> Referrer
   * 0.02% -> Market/Limit
2. **Closing a trade: 0.07%**
   * 0.05% -> Ecosystem
   * 0.02% -> Market/Limit

### Forex (Tier 1)

1. **Opening a trade: 0.01%**
   * 0.008% -> Ecosystem
     * 0.002-0.003% -> Referrer
   * 0.002% -> Market/Limit
2. **Closing a trade: 0.01%**
   * 0.008% -> Ecosystem
   * 0.002% -> Market/Limit

### Forex (Tier 2)

1. **Opening a trade: 0.015%**
   * 0.012% -> Ecosystem
     * 0.003-0.004% -> Referrer
   * 0.003% -> Market/Limit
2. **Closing a trade: 0.015%**
   * 0.012% -> Ecosystem
   * 0.003% -> Market/Limit

### US Stocks

1. **Opening a trade (0.08%)**
   * 0.06% -> Ecosystem
     * 0.016-0.02% -> Referrer
   * 0.02% -> Market/Limit
2. **Closing a trade (0.08%)**
   * 0.06% -> Ecosystem
   * 0.02% -> Market/Limit



## **Lifecycle of a Trade**

### Opening Fee & Closing Fee

Let's say we use **100 USDT** at **50x** leverage to long ETH/USD. The fee is applied to leveraged amount: **5,000 USDT**.

5,000 \* 0.07% = **3.5 USDT fee**

**5,000 USDT** is the  total position size



### **Borrowing Fee**s

Borrowing fees are applied to trades while they are open. Borrowing fee rate per hour, charged based on the **borrowed amount = (total position size - collateral size)**, rate is displayed on the trade page.



### Overnight Interest

Overnight Interest are applied to trades while they are open. Overnight interest, UTC+8, charged daily at 00:00, charged based on the **borrowed amount = (total position size - collateral size)**, rate is displayed on the trade page.



### Liquidation Fees

No liquidation fees.



### Liquidation Prices

Trades liquidation prices can **get closer** over time if you **pay borrowing fees**.

# 📚 MST Economic

## Overview

The market regulation mechanism of MST depends on the market regulation mechanism of the MST-USDT Vault.



## MST-USDT Vault&#x20;

$$f(TVL) = Σ(Accumulated Deposits of USDT) + ΔPNL$$

$$f(PRICE) =  Previous Price - Dividends - Interest$$

$$f(CR) = USDT-TVL / MST-USDT *100%$$

$$f(MST-USDT) = TVL / PRICE$$



## Operation Principle

MST-USDT Vault is a USDT vault following the ERC-4626 standard. ERC-4626 is a standard API   for tokenized yield vaults, representing shares of individual underlying ERC-20 assets. In this case, the MT-USDT share represents the underlying USDT asset. The vault acts as the counterparty for all trades on the platform:

* When traders win (positive PnL), their rewards are received from the vault.
* When traders lose (negative PnL), their losses are sent to the vault.
* LP Insurance Mechanism: To ensure minimal loss to market LP funds, a market LP fund compensation mechanism will be initiated. The mechanism is depicted in the diagram below



## MST Annual Inflation Rate:&#x20;

The maximum daily minting of MST is 0.05% of the current circulating supply, resulting in an annual inflation rate of 18.25%.



## Epoch system

Epoch system provides open PnL data to the vault in a decentralized manner, so the vault better understands its collateralization ratio. Calculating open PnL is too computationally expensive to do in real-time, on-chain.&#x20;

There are two states the epoch system can be in:

* **Withdraw window** - the period before open PnL values are being received and stakers may make withdraw-related actions (both requests and withdraws).
* **Open PnL window** - the period before the epoch closes where the protocol requests open PnL snapshots from oracles. It makes multiple requests to a network of oracles, taking the median value, finally averaging across the request periods. This PnL value is then used in the succeeding epoch.



## Withdraw locks

For the security of the vault, and to prevent stakers from front-running PnL changes, USDT can't be withdrawn immediately. Instead it must go through a withdraw request system.

Depending on the collateralization ratio of the vault, a staker may withdraw either 1, 2, or 3 epochs after making a request. The higher collateralization ratio, the shorter the lock period.

If a staker misses their withdraw window, they must make a new request.

# 🐛 Bug Bounty

### Program Overview <a href="#program-overview" id="program-overview"></a>

Monsters.exchange is building the decentralized finance ecosystem of the future, featuring a capital-efficient decentralized leveraged trading platform on Arbitrum.For more information about Monsters.exchange, please visit website ：[​<mark style="color:purple;">monsters.exchange</mark>](https://monsters.exchange/) ​This bug bounty program is dedicated to identifying vulnerabilities within their smart contracts, website, and applications to prevent the following scenarios:

1. 1.Direct theft of user funds, whether at rest or during transmission, except unclaimed yield.
2. 2.Permanent freezing of funds.
3. 3.Insolvency.
4. 4.Theft of unclaimed yield.
5. 5.Permanent freezing of unclaimed yield.
6. 6.Temporary freezing of funds for at least 1 day.

By participating in this bug bounty program, you play an integral role in ensuring the security and robustness of the Monsters.exchange decentralized finance ecosystem. Your efforts contribute to a safer environment for users and their assets. For detailed information about the program's scope, rewards, and rules, please refer to the provided documentation or the Monsters.exchange website.

### Submission Process <a href="#submission-process" id="submission-process"></a>

#### To participate in the bug bounty program, follow these steps: <a href="#to-participate-in-the-bug-bounty-program-follow-these-steps" id="to-participate-in-the-bug-bounty-program-follow-these-steps"></a>

* Join the Discord group: ​[<mark style="color:purple;">discord.gg/zSckQTBj</mark>](https://discord.gg/zSckQTBj)
* Contact the administrators to be added to the bug bounty program group.
* Once added, you can submit the details of the identified vulnerabilities and provide your reward address for payout.

By following this process, you can contribute to the security of the platform and potentially earn rewards for your efforts. Make sure to review the program's documentation and guidelines for a comprehensive understanding of the submission process and eligibility criteria.

### Rewards Based on Threat Level <a href="#rewards-based-on-threat-level" id="rewards-based-on-threat-level"></a>

Rewards are distributed according to the impact of the vulnerability based on the Vulnerability Severity Classification System. This is a simplified scale, categorized by the impact of the reported vulnerabilities, differentiating between websites/apps, smart contracts, and blockchains/DLTs.All web/app vulnerability reports must include a Proof of Concept (PoC) with an end-effect that impacts an asset within the scope, in order to be considered for a reward. Explanations and statements will not be accepted as PoC; code is required.Rewards are primarily based on risk funds, considering PR and branding aspects at the discretion of the team. The minimum reward is $5,000.00 USD, with the maximum reward for critical smart contract vulnerabilities capped at 10% of economic loss.Payouts will be managed directly by the Monsters team, denominated in USD. However, rewards will be paid in MST and USDT, with the ratio determined by the team.By participating in this bug bounty program, you contribute to enhancing the security of the Monsters ecosystem. Make sure to consult the provided program documentation and guidelines for a comprehensive understanding of the reward structure and terms. Your efforts play a crucial role in maintaining a safe and robust platform.

#### Smart Contract <a href="#smart-contract" id="smart-contract"></a>

| **Level** | **Payout**        |
| --------- | ----------------- |
| Critical  | Up to USD $50,000 |
| High      | USD $25,000       |
| Medium    | USD $15,000       |
| Low       | USD $5,000        |

**Impacts Within the Smart Contract Scope**

This bug bounty program only accepts the following impacts as within the scope. Even if other impacts affect certain items in the assets in scope table, they are not considered to be within scope.

| **type**                                                                                  | **level** |
| ----------------------------------------------------------------------------------------- | --------- |
| Insolvency                                                                                | Critical  |
| Permanent freezing of funds                                                               | Critical  |
| Direct theft of any user funds, whether at-rest or in-motion, other than unclaimed yield  | Critical  |
| Theft of unclaimed yield                                                                  | High      |
| Permanent freezing of unclaimed yield                                                     | High      |
| Temporary freezing of funds for at least 1 day                                            | High      |
| Miner-extractable value (MEV)                                                             | Medium    |
| Block stuffing for profit                                                                 | Medium    |
| Griefing (e.g. no profit motive for an attacker, but damage to the users or the protocol) | Medium    |
| Unbounded gas consumption                                                                 | Medium    |
| Theft of gas                                                                              | Medium    |
| Smart contract unable to operate due to lack of funds                                     | Low       |
| Smart contract fails to deliver promised returns, but doesn’t lose value                  | Low       |

​

#### Websites and Applications <a href="#websites-and-applications" id="websites-and-applications"></a>

| Level    | Payout      | PoC          |
| -------- | ----------- | ------------ |
| Critical | USD $20,000 | PoC Required |
| High     | USD $5,000  | PoC Required |
| Medium   | USD $2,500  | PoC Required |
| Low      | USD $1,000  | PoC Required |

**Impacts Within the Websites and Applications Scope**

This bug bounty program only accepts the following impacts as within the scope. Even if other impacts affect certain items in the assets in scope table, they are not considered to be within scope.

| **type**                                                                                            | **level** |
| --------------------------------------------------------------------------------------------------- | --------- |
| Ability to execute system commands                                                                  | Critical  |
| Extract Sensitive data/files from the server such as /etc/passwd                                    | Critical  |
| Taking Down the application/website                                                                 | Critical  |
| Stealing User Cookies                                                                               | Critical  |
| Signing transactions for other users                                                                | Critical  |
| Redirection of user deposits and withdrawals                                                        | Critical  |
| Wallet interaction modification resulting in financial loss                                         | Critical  |
| Subdomain takeover resulting in financial loss (applicable for subdomains with addresses published) | Critical  |
| Direct theft of user funds                                                                          | Critical  |
| Tampering with transactions submitted to the user’s wallet                                          | Critical  |
| Submitting malicious transactions to an already-connected wallet                                    | Critical  |
| Spoofing content on the target application (Persistent)                                             | High      |
| Users Confidential information disclosure such as Email                                             | High      |
| Subdomain Takeover without financial loss (applicable for subdomains with no addresses published)   | High      |
| Privilege escalation to access unauthorized functionalities                                         | High      |
| Changing details of other users without direct financial impact (CSRF)                              | Medium    |
| Third-Party API keys leakage that demonstrates loss of funds or modification on the website         | Medium    |
| Redirecting users to malicious websites (Open Redirect)                                             | Medium    |
| Framing sensitive pages leading to financial loss (ClickJacking)                                    | Low       |
| Any impact involving a publicly released CVE without a working PoC                                  | Low       |

​

### Out of Scope and Rules <a href="#out-of-scope-and-rules" id="out-of-scope-and-rules"></a>

#### The following vulnerabilities are not included in the reward scope of this bug bounty program: <a href="#the-following-vulnerabilities-are-not-included-in-the-reward-scope-of-this-bug-bounty-program" id="the-following-vulnerabilities-are-not-included-in-the-reward-scope-of-this-bug-bounty-program"></a>

1. 1.Attacks that the reporter has already exploited themselves, resulting in damage.
2. 2.Attacks requiring access to leaked keys/credentials.
3. 3.Attacks requiring access to privileged addresses (governance, strategist).
4. 4.Smart Contracts and Blockchains

* Incorrect data supplied by third-party oracles.
* Excluding oracle manipulation/flash loan attacks.
* Basic economic governance attacks (e.g., 51% attack).
* Lack of liquidity.
* Best practice critiques.
* Don Quixote attacks.
* Centralization risks.

#### Websites and Applications <a href="#websites-and-applications-1" id="websites-and-applications-1"></a>

**The following vulnerabilities are not considered within scope for this bug bounty program:**

* Theoretical vulnerabilities without any evidence or demonstration.
* Content spoofing / Text injection issues.
* Self-XSS.
* Captcha bypass using OCR.
* CSRF with no security impact (logout CSRF, change language, etc.).
* Missing HTTP security headers (e.g., X-FRAME-OPTIONS) or cookie security flags (e.g., "httponly").
* Server-side information disclosure such as IPs, server names, and most stack traces.
* Vulnerabilities used to enumerate or confirm the existence of users or tenants.
* Vulnerabilities requiring unlikely user actions.
* URL redirects (unless combined with another vulnerability to produce a more severe vulnerability).
* Lack of SSL/TLS best practices.
* DDoS vulnerabilities.
* Attacks requiring privileged access from within the organization.
* Feature requests.
* Best practices.
* Vulnerabilities primarily caused by browser/plugin defects.
* Any vulnerability exploit requiring CSP bypass resulting from a browser bug.

#### The following activities are prohibited by this bug bounty program: <a href="#the-following-activities-are-prohibited-by-this-bug-bounty-program" id="the-following-activities-are-prohibited-by-this-bug-bounty-program"></a>

1. 1.Any testing with mainnet or public testnet contracts; all testing should be done on private testnets.
2. 2.Any testing with pricing oracles or third-party smart contracts.
3. 3.Attempting phishing or other social engineering attacks against our employees and/or customers.
4. 4.Any testing with third-party systems and applications (e.g., browser extensions) as well as websites (e.g., SSO providers, advertising networks).
5. 5.Any denial of service attacks.
6. 6.Automated testing of services that generates significant amounts of traffic.
7. 7.Public disclosure of an unpatched vulnerability in an embargoed bounty.

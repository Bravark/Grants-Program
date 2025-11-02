# Name of your Project

> [!NOTE]
> This document will be part of the terms and conditions of your agreement and, therefore, needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines (except for the title)! Lines starting with a `>` (such as this one) should be removed. Please use markdown instead of HTML (e.g., `![](image.png)` instead of `<img>`).
>
> See the [Grants Program Process](https://grants.web3.foundation/docs/process) on how to submit a proposal.

- **Team Name:** Legal name of your team (e.g. JsonCorp)
- **Payment Details:**
  - **DOT**: For the **DOT** compensation, please provide a Polkadot address (e.g. 15oF4...).
  - **Payment**: For the **USDC** portion of the payment, please provide a Polkadot AssetHub address and the currency (e.g. 15oF4... (USDC)). 
- **[Level](https://grants.web3.foundation/docs/Introduction/levels):** 1, 2 or 3

> [!IMPORTANT]
> *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*


### Overview
Deserialize is a multi-chain DeFi trading platform and SDK that unifies fragmented liquidity across DEXs using an AI-powered routing engine.
It enables efficient swaps, limit orders, DCA, Options Trading and perps with zero fees on swap, profit-sharing, and multi-chain support.

Deserialize is a DEX aggregator for Polkadot, enabling seamless token swaps across parachains by finding the best routes and aggregating liquidity, unlocking efficient cross-chain trading and boosting adoption in the ecosystem
We’re building on Polkadot because its multi-chain architecture and shared security make it ideal for seamless cross-parachain trading.

### Project Details

Deserialize is an all-in-one DeFi trading platform designed to give users complete control over their trading strategies.
At its core is our DEX aggregator, powered by an exceptional algorithm that's engineered to always find the best swap and trade routes for users. The aggregator intelligently hops between intra-DEX and inter-DEX pools, scanning multiple liquidity sources to deliver the most optimal outcomes. In doing so, it naturally brings balance to prices across pools on the blockchain, ensuring users get maximum value on every trade.
To give users more flexibility, we've integrated Limit Orders, allowing traders to buy or sell tokens at their desired price points. This intent-based swap system operates on a taker/filler model—user orders are exposed to fillers through our endpoints, who then execute these orders based on matching intent. This means your trades happen exactly when and how you want them.
We further empower users with Perpetuals, giving traders the ability to long or short any token based on their market predictions without needing to directly own the underlying assets. Additionally, users can leverage their positions by borrowing from the DEX, amplifying their potential gains (and managing their risk accordingly).
Users also gain access to Options Trading, a powerful tool for strategic traders. Options give you the right, but not the obligation, to buy (call option) or sell (put option) a token at a predetermined price before a specific expiration date. This allows for sophisticated strategies like hedging portfolio. 
DCA (Dollar-Cost Averaging) is another powerful option available to users, enabling them to automatically spread their purchases over time at regular intervals.
This strategy removes the stress of timing the market and helps smooth out price volatility, making it ideal for long-term investors who want to build positions steadily without the emotional burden of trying to catch the perfect entry point.
An integrated arbitrage distribution mechanism captures profits from price inefficiencies and automatically redistributes them to participating traders, further incentivizing liquidity provision and activity across the Polkadot ecosystem. Security is central to the design: critical contracts undergo formal verification and third-party audits, transactions are simulated off-chain to prevent errors before execution, and upgrades are governed via multi-signature controls, balancing flexibility with safety.
Off-chain, Deserialize provides structured APIs that allow developers and dApps to query optimal trade routes, monitor liquidity pools, and track arbitrage opportunities in real time. These APIs are complemented by a React/Next.js frontend, enabling wallet integration and one-click token swaps, while cloud-based infrastructure and custom indexing ensure low-latency, reliable access to parachain data.
The full technology stack is comprehensively documented, detailing routing algorithms, liquidity aggregation logic, and arbitrage mechanisms. Protocols deployed include the DEX aggregation protocol for optimized trades, cross-parachain communication protocols to support interoperability, and security protocols for safe contract upgrades. By integrating tightly with Polkadot’s multi-chain environment, Deserialize lowers barriers to cross-parachain liquidity, drives efficient trading, and positions itself as a key infrastructure layer supporting the growth and adoption of the Polkadot ecosystem.

Deserialize as of Aug 22, 2025
Processed over 140,180 transactions
Over $20m in transaction volume
35,000+ users



### Ecosystem Fit

Deserialize fits into the Polkadot ecosystem as an all-in-one DeFi trading platform that allows users to perform a number of trading activities all in one interface.
By leveraging XCM and Polkadot’s secure infrastructure, Deserialize enables zero-fee swap trading, AI-powered routing, and cross-chain automation, helping users trade seamlessly while strengthening Polkadot’s DeFi network through developer tools, ecosystem integrations, and active community growth.

Our target audience includes DeFi traders, developers, and ecosystem partners/ecosystem individuals within the Polkadot network. 
Deserialize meets key needs by solving fragmented liquidity, high trading fees, and limited cross-chain access. In other words, Deserialize meets the need for a secure, low-cost, interoperable trading solution and cross-parachain liquidity efficiency within the Polkadot ecosystem.
- How did you identify these needs? Please provide evidence in the form of (scientific) articles, forum discussions, case studies, or raw data.
Literature & academic research showing liquidity fragmentation across DEXs and AMMs. arXiv+1
Industry reports and SoK papers documenting bridge/ cross-chain risks and large losses, which show why secure cross-chain design and reduced bridge reliance matter. arXiv+1
On-chain / market signals about high gas fees and UX friction (historical spikes and ongoing fee variability) that push users towards lower-cost chains and aggregators. YCharts+1
Case studies and blog analyses of DEX aggregators (1inch, Matcha, etc.) demonstrating how aggregation and smarter routing reduce price impact and solve fragmented liquidity. CCN.com+1
Polkadot developer docs and community discussions showing XCM and interoperability as a practical solution for cross-chain messaging and secure parachain integrations — aligning directly with Deserialize’s multi-chain goals. docs.polkadot.com+1
Plus: our own product data and goals from the Deserialize docs (140,180+ tx, $20M volume, 40k users; MVP focus on zero-fee trading, AI routing, audits & community growth)  i.e., raw project evidence that these needs are real for our users.

Several well-known projects in other ecosystems do parts of what Deserialize does but not all 
There are projects in the Polkadot / Kusama / Substrate ecosystem that share some similarities with Deserialize (e.g Bifrost, HydraDX, ZKLiquid, Zenlink). Deserialize offers a wider scope that focuses on routing across liquidity pools + parachains + SDK integration + users earn arbitrage based on the pay of the pools at that time 

## Team :busts_in_silhouette:

> [!IMPORTANT]
> Please note that the data provided in this section is for administrative and informational purposes only. All beneficiaries of a grant must also be listed in the KYC/KYB process during the application phase. See our [FAQ](https://grants.web3.foundation/docs/faq#what-is-kyckyb-and-why-do-i-have-to-provide-this-data) for more info.

### Team members

- Name of team leader
Demitchy
- Names of team members
Zach
Ikeoluwa
Korede
Tunde


### Contact
 
- **Contact Name:** Mitchel Obiyor
- **Contact Email:** Demitchy1@gmail.com
- **Website:** deserialize.xyz

### Legal Structure

- **Registered Address:** No 15 Aiyetoro street, Akoka, Lagos

### Team's experience



### Team Code Repos
- https://github.com/bravark



## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://grants.web3.foundation/docs/rfps) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Web3 Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/Support%20Docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe *the functionality we should expect in as much detail as possible*, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We *recommend* that teams structure their roadmap as 1 milestone ≈ 1 month.

> [!CAUTION]
> If any of your deliverables are based on somebody else's work, make sure you work and publish *under the terms of the license* of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Projects that submit other people's work without proper attribution will be immediately terminated.**

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested.
- **DOT %:** Percentage of Total Costs to be paid in (vested) DOT (≥ 50%)

### Milestone 1 Example — Basic functionality

- **Estimated duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

> [!NOTE]
> **The default deliverables 0a-0d below are mandatory for all milestones**, and deliverable 0e at least for the last one.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense. See the [delivery guidelines](https://grants.web3.foundation/docs/Support%20Docs/milestone-deliverables-guidelines#license) for details. |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. See the [delivery guidelines](https://grants.web3.foundation/docs/Support%20Docs/milestone-deliverables-guidelines#documentation) for details. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. See the [delivery guidelines](https://grants.web3.foundation/docs/Support%20Docs/milestone-deliverables-guidelines#testing-guide) for details. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language, and medium should reflect your target audience described above.) |
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate module: Y | The Y Substrate module will... |
| 3. | Substrate module: Z | The Z Substrate module will... |
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 5. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 6. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will...

http://docs.deserialize.xyz/api/swap-api/docs/


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

...


## Future Plans

Deserialize will generate revenue through arbitrage profit-sharing on user swaps, trading fees from perpetuals and options, and integration/partner fees from businesses and platforms that build on or integrate with Deserialize.
We will drive growth through strategic collaborations and partnerships with other products in the ecosystem, while also building a strong, engaged community of users who genuinely believe in the project. Community members will be incentivized and rewarded for their participation and contribution.
The long term we plan to become the biggest DeFi trading platform.


## Referral Program (optional) :moneybag:

You can find more information about the program [here](https://grants.web3.foundation/docs/referral-program).

- **Referrer:** Bekka
- **Payment Address:** 143KcMTK2Z5k3uLu8jqG9ib6sjD3fbBkA7BEsX7G2DqRW5cw


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** We got to know about the Grant through Polkadot Africa


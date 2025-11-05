# Deserialize

- **Team Name:** Delabz
- **Payment Details:**
  - **DOT**: 143KcMTK2Z5k3uLu8jqG9ib6sjD3fbBkA7BEsX7G2DqRW5cw
  - **Payment**: 143KcMTK2Z5k3uLu8jqG9ib6sjD3fbBkA7BEsX7G2DqRW5cw
- **Level:** 3

### Project Overview
Deserialize is an all-in-one DeFi trading platform  that features an efficient swap aggregator, Perp dex, limit orders, Grid Trading, Token screener, Options Trading and DCA.

Deserialize as of October 30th, 2025
Processed over 650,195 transactions
Over $40m in transaction volume
45,000+ users all on Eclipse and 0G

### Project Details

Deserialize is a defi focused product, built to make life easier for users & builders alike. We feature in-depth trading tools/features for both EVM & SVM powered ecosystems. Our features consist of:

#### SWAP AGGREGATOR
Deserialize MVP existed as a DEX aggregator, powered by our custom 'serialize' algorithm. We created an infrastructure which is engineered to always find the best swap & trade routes for users. The aggregator intelligently routes intra-DEX and inter-DEX, routing liquidity sources to deliver the most optimal outcomes on atomic swaps. In doing so, it automatically captures arbitrage opportunities when available, giving users the ability to make money on swaps. To aid the devs in integrating our infra, we created
- SDK (To enable anyone integrate the swap aggregator in their backend)
- API (To enable easier use of the SDK especially in frontend)
- UI WIDGET (This allows you launch your own swap page without writing any code)

#### PERP DEX
We further empower users with Perpetuals, giving traders the ability to long or short a handful of supported tokens without needing to directly own the underlying assets. Additionally, users can leverage their positions by borrowing from the DEX, amplifying their potential gains (and managing their risk accordingly).

#### LIMIT ORDER
To give users more flexibility, we've integrated CLOB limit Orders, allowing traders to buy or sell tokens at their desired price points. This intent-based swap system operates on a taker/filler model—user orders are exposed to fillers through our endpoints, who then execute these orders based on matching intent. This means your trades happen exactly when and how you want them.

#### GRID TRADING
Grid trading is a strategy that gives user the ability to enjoy every ride of their trade-the highs and lows of a token- and this is done automatically without users having to go back and forth 

#### TOKEN SCREENER
Our Token screener provides users with all available token-recently launched or existing- on a blockchain. it gives every single detail of all the tokens available;Market Cap, buys, sell, 24h volume. Also with the ability to purchase tokens while on this view.


#### OPTIONS TRADING
Options give you the right, but not the obligation, to buy (call option) or sell (put option) a token at a predetermined price before a specific expiration date. This allows for sophisticated strategies like hedging portfolio. 

#### DCA
Dollar-Cost Averaging enables users to spread their purchases over time at regular intervals, allowing them average their postions in any token over time.
This strategy removes the stress of timing the market and helps smooth out price volatility, making it ideal for long-term investors who want to build positions steadily without the emotional burden of trying to catch the perfect entry point.


### Ecosystem Fit

Deserialize fits into the Polkadot ecosystem as an all-in-one DeFi trading platform that allows users to perform a number of trading strategies all in one interface.
By leveraging XCM and Polkadot’s secure infrastructure, Deserialize enables zero-fee swap trading, helping users trade seamlessly while strengthening Polkadot’s DeFi network through developer tools, ecosystem integrations, and active community growth.

Our target audience includes DeFi traders, developers, and ecosystem partners/ecosystem individuals within the Polkadot network. 
Deserialize meets key needs by bringing the whole defi experience in one place, simultaneously tackling fragmented liquidity, high trading fees, and limited access. In other words, Deserialize meets the need for a secure, low-cost, interoperable trading solution and cross-parachain liquidity efficiency within the Polkadot ecosystem.

Several well-known projects in other ecosystems do parts of what Deserialize does but not all 
There are projects in the Polkadot / Kusama / Substrate ecosystem that share some similarities with Deserialize (e.g Bifrost, HydraDX, ZKLiquid, Zenlink). Deserialize offers a wider scope that focuses on routing across liquidity pools + parachains + SDK integration + users earn arbitrage based on the pay of the pools at that time 

## Team :busts_in_silhouette:

### Team members

- Name of team leader:
Demitchy
- Names of team members:
Backend Engineer & CTO: Zach
Project Manager & Data Scientist: Ikeoluwa
FrontEnd Engineer: Korede
Backend Developer & Smart Contract Dev:Tunde
Lead Designer: Precious
CMO: Inioluwa

### Contact
 
- **Contact Name:** Mitchel Obiyor
- **Telegram:** @demitchy
- **Contact Email:** Demitchy1@gmail.com
- **Website:** deserialize.xyz

### Legal Structure

- **Registered Address:** No 15 Aiyetoro street, Akoka, Lagos

### Team's experience
Our team consists of very experienced individuals well versed in the DeFi trading. We have built other DeFi trading platforms which include Debonk- a telegram trading bot
Defungiz- An NFT market place and launchpad
Dextopus- A Meta-bridging protocol
DeMeta- A token launchpad 
Decane- A wallet. 
We have also partnered with a number of protocols in the space; EclipseFND, 0G_labs, Relay, Hyperbridge, Nightly, Invariant, Orca among many others. 

### Team Code Repos
- https://github.com/bravark

## Development Status :open_book:

Currently Our Dex Aggregator, and token screener are live and running on Base, 0G_Labs and Eclipse. Our Limit Order and Perps are fully developed and ready to be deployed and live. we are developing Options Trading and Grid Trading, we have our team fully dedicated to this in order to bring all this incredible features to Polkadot.

## Development Roadmap :nut_and_bolt:

### Overview
- **Estimated duration:** In progress
- **FTE:**  1,5
- **Costs:** 50,000 USD
- 

### Milestone 1  - Core Functionality
Swap Aggregator, Limit Order, Perp, Token Screener
- **Estimated duration:** Completed
- **FTE:**  1,5
- **Costs:** 20,000 USD



| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0
| **0b.** | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can Swap, trade perps, create a limit order and explain all the term and info on the dex screener.|
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests.
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| **1.** | Dex Aggregator | Provide our powerful serialize algorithm that route through DEX's to provide the best output for users and  |
| **2.** | Limit Order| Provide our platform where users can buy and sell their tokens at a target price and expose our API to filers who would match the orders |
| **3.** | Perp Dex | Provide our powerful serialize algorithm that route through DEX's to provide the best output for users and  |
| **4.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness.  |
| **5.** | API Documentation | Provide our API Documentation for developers to integrate and use |
| **6.** | Specific Dex Routing | Our Algorithm has inter and intra routing we would allow users select a particular Dex  |
| **7.** | Split Transaction | Our Serialize algorithm would have a split transaction that divides a single order into multiple smaller executions to achieve better price and reduce slippage.|

### Milestone 2  — Additional features
 
 DCA, Options Trading and Grid Trading
- **Estimated Duration:** 3 month
- **FTE:**  1,5
- **Costs:** 30,000 USD

...
| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0|
| **0b.** | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can Swap, trade perps, create a limit order and explain all the term and info on the dex screener.|
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests.
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| **1.** | API Documentation | Provide our API Documentation for developers to integrate and use|
| **2.** | Options Trading | Implement the logic and deploy the smart contract  |
| **3.** | DCA |  Deploy the smart contract that enables users to DCA |
| **4.**| Grid Trading |Deployment of the smart contract|


## Future Plans
The long term we plan to become the biggest DeFi trading platform.

- Deserialize will generate revenue through arbitrage profit-sharing on user swaps,
- Trading fees from perpetuals and options, and
- integration/partner fees from businesses and platforms that build on or integrate with Deserialize.

We will drive growth through strategic collaborations and partnerships with other products in the ecosystem, while also building a strong, engaged community of users who genuinely believe in the project. Community members will be incentivized and rewarded for their participation and contribution.


## Referral Program (optional) :moneybag:

- **Referrer:** Bekka


## Additional Information :heavy_plus_sign:

We got to know about the Grant through Polkadot Africa


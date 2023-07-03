# FAQ

**What is Zorro?**\
Zorro is a cross-chain protocol that seamlessly facilitates investing in AMMs by automating transactions with one click.\


**What is the difference between multi-chain and cross-chain?**\
The terms "multi-chain" and "cross-chain" are often used interchangeably in DeFi but there is an important distinction between the two.\
Most protocols these days are multi-chain which means that they have vaults on multiple chains. However, the chains are not connected meaning if you want to invest on a given chain, you need to have funds on that chain, hold the native token to pay for gas and withdraw the funds and bridge them if you want to invest them on another chain. If a protocol has its own token, the token is also replicated across chains and held separately.\
Cross-chain refers to the ability to move funds seamlessly from one chain to another and can even go as far as abstracting the need to understand which chain you are on. You will know that a protocol is cross-chain when you can easily move funds from one chain to another on the protocol without having to rely on external bridges.\
Important: CeFi projects that move your funds from one chain to another might be cross-chain by that definition but they do so by holding funds offline on the different chains which exposes you to the risk of not fully controlling the funds yourself thus it's important to make sure the project is not only cross-chain but also fully decentralized and trustless.

\
**What is the difference between CeFi and DeFi?**\
A centralized exchange or project (e.g., Coinbase, Kraken, FTX, Celsius, BlockFi) is a “central” authority that manages users’ funds off chain. In exchanges, funds from one chain are being sent to the exchange which manages the funds and grants the equivalent amount on another chain as the users request it. Users must trust the central authority with their funds which are neither on-chain nor trustless. In addition, users usually have to create a login and verify their identity in order to use the service. The failures of centralized projects over the recent months (Celsius, BlockFi, FTX, etc.) have highlighted the inherent risk of relying on a small group people having control over your funds and the risk of losing access to the funds either through an exogenous event (e.g., bank run) or malicious activity by the people in charge of the centralized project.\
DeFi on the other hand is by definition decentralized and in an ideal case trustless, meaning the protocol makes decisions based on logic in the code rather than humans and thus users fully and anonymously (no need to create a login) control their funds. DeFi has its own issues, most importantly, code and logic issues which can subject it to hacks but at least the control is fully with the users.\


**What is an AMM?**\
In traditional finance, market makers provide trading services for investors to keep financial markets liquid. Market makers display buy and sell quotations for a guaranteed number of shares.  Once the market makers receive an order from a buyer, they immediately sell off their position of shares from their own inventory, making it easier for investors and traders to buy and sell. In DeFi, AMMs or automated market makers (like SushiSwap, Trader Joe, UniSwap) allow digital assets to be traded in a permissionless and automatic way by using liquidity pools rather than a traditional market of buyers and sellers. Most liquidity pools consist of two tokens whose prices are determined by a constant mathematical formula or through a modified formula in concentrated liquidity pools in UniSwap V3 and projects based on the same model.\


**What is a liquidity pool?**\
A liquidity pool on AMMs is a “pool of funds”, usually two tokens (e.g., BTC and ETH) that allows buyers and sellers in DeFi to execute permissionless trades without intermediaries on-chain. If you want to buy BTC, you can go on SushiSwap and buy it from a BTC - ETH liquidity pool. The price is determined by a mathematical formula. If an AMM has Bitcoin (BTC) and Ethereum (ETH), two volatile assets, every time BTC is bought, the price of BTC goes up as there is less BTC in the pool than before the purchase. Conversely, the price of ETH goes down as there is more ETH in the pool. The pool stays in constant balance, where the total value of BTC in the pool will always equal the total value of ETH in the pool. Only when new liquidity providers join in the pool will expand in size.\


**What is a liquidity provider?**\
In order to facilitate smooth trades in DeFi, liquidity pools need to have sufficient liquidity in form of the tokens in pools that users want to buy and sell. Liquidity is provided by other users who lock their tokens in these pools. These so-called “liquidity providers” are incentivized to add their liquidity to the pool by receiving a share from the trading fees that buyers and sellers incur. Anyone with an internet connection and in possession of any type of ERC-20 tokens can become a liquidity provider by supplying tokens to an AMM’s liquidity pool.\


**What is a vault?**\
Vaults on Zorro are liquidity pools or single token lending pools from AMMs and lending protocols that benefit from Zorro’s investment automation across chains. Zorro focuses on vaults from AMMs and protocols that have not been hacked, have been around for long, have been audited multiple times, have been vetted by crypto industry experts and have high levels of liquidity.\


**Which AMMs does Zorro offer access to**\
Zorro emphasizes safety and security above everything else as DeFi projects are still frequently subject to rug pulls, hacks and other scams.\
As a result, Zorro is very selective in the projects it lists to ensure highest levels of safety for its users.\
All vaults listed on Zorro come from projects that have not been involved in hacks or scams, that have been extensively audited, around for some time, vetted by crypto industry experts and have high levels of liquidity.\
\
Currently Zorro lists vaults from the following projects (more to come soon):\
1\) Trader Joe (AMM on Avalanche): [https://traderjoexyz.com/avalanche/pool](https://traderjoexyz.com/avalanche/pool)\
2\) Pangolin (AMM on Avalanche): [https://app.pangolin.exchange/](https://app.pangolin.exchange/)\
3\) SushiSwap (AMM on Arbitrum, Polygon): [https://www.sushi.com/pools](https://www.sushi.com/pools)\
4\) QuickSwap (AMM on Polygon): [https://quickswap.exchange/#/pools/v2](https://quickswap.exchange/#/pools/v2)\


**Which tokens does Zorro offer exposure to**\
Zorro offers exposure to token pairs on the AMMs listed with a focus on vaults with sufficient liquidity (TVL) to minimize slippage and a high transaction volume. Coverage includes but is not limited to major bluechip tokens (BTC, ETH, AVAX, MATIC etc.), stablecoins (USDC, USDT, DAI, etc.) and tokens from major DeFi projects (LINK, UNI, JOE, etc.). You can always request the listing of additional tokens or vaults <mark style="color:red;">here</mark>.\


**What happens when I withdraw from a vault?**\
When you withdraw your funds from a Zorro vault, you receive your funds back (initial deposit and accumulated rewards) in **USDC**. Zorro does not return funds in the token currency of the vault. Receiving funds back in a stablecoin like USDC allows you to decide what to do with your gains next without the risk of being exposed to volatile token movements.\


**What is impermanent loss?**\
Impermanent loss is a risk involved with providing liquidity to liquidity pools in DeFi protocols on AMMs and yield aggregators. It is the difference in value between depositing 2 crypto tokens within an AMM-based liquidity pool or simply holding them in a crypto wallet.\
\
Essentially, it occurs when depositing them into an automated market maker and then withdrawing them at a later date results in a loss, compared to if you had just HODL'd and left them in your wallet. In fact, you may not actually lose any money, but rather your gains are less relative to if you had just left your assets untouched. Inversely, losses can be amplified depending on how the market moves.\
\
The phrase earns its name because any losses are only accepted once the funds are withdrawn from the liquidity pool. Until then, any losses are only on paper and may reduce or disappear completely depending on how the market changes.\
For more information check out this definition and example: https://academy.binance.com/en/articles/impermanent-loss-explained\


**What are the fees on the Zorro platform?**\
Zorro charges a fee for each trade that covers operational costs, gas fees and cross-chain related costs. The fee is transparently displayed before confirming the trade so users can see what they are being charged.\
1\) Deposits: A deposit has a base fee of 1% (of the deposit amount) to cover operations, security, platform maintenance in addition to gas/cross-chain fees which for most EVM chains other than Ethereum are negligibly small as Zorro batches several steps to reduce fees (\~$0.01 - $1)\
2\) Transfers: Transfers have a base fee of 0.5% to to cover operations, security, platform maintenance in addition to gas/cross-chain fees\
3\) Withdrawals: Withdrawals only incur gas/cross-chain fees\
\
Keep in mind that Zorro is gasless meaning Zorro manages all gas fees for the users so that users do not need to carry the chain-native gas token. Gas fees are automatically deducted from the USDC transaction value.\


**Are Zorro fees high or low compared to other protocols?**\
Zorro combines the ease of use and convenience that historically only CeFi platforms provided with the control, anonymity and immutability of DeFi platforms.\
Exchanges like Coinbase usually charge fees upwards of 4% and the fees on DeFi projects range from 1% (most concentrated liquidity position on UniSwap) to 10% (performance fee model) on Yearn Finance.\
\

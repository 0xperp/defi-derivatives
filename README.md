# DeFi Derivative Landscape
## A hopefully comprehensive guide to the defi derivative landscape

## Projects
#### Options
- [Opyn](https://opyn.co/) - Orderbook options protocol with power perpetuals and power perpetual strategies launching soon
  - [Trade](https://v2.opyn.co/#/)
  - [Gamma Portal](https://gammaportal.xyz/#/)
  - [Opyn Analytics](https://opyn-dashboard-2.netlify.app/dashboards/default)
  - [Opyn Developer Kit](https://medium.com/opyn/introducing-opyn-developer-toolkit-2bfd5bcc7a92)
  - Squeeth (ETH^2)
    - [Intro to Squeeth](https://twitter.com/wadepros/status/1444690047639461893)
    - [Crab Strategy](https://twitter.com/wadepros/status/1476973710150152194)
    - [Understanding Perpetual Vaults in DeFi: Options Strategies](https://medium.com/opyn/understanding-perpetual-vaults-in-defi-structured-products-with-underlying-options-strategies-27610254475e)
    - [Squeeth insides volume 1: funding and volatility](https://medium.com/opyn/squeeth-insides-volume-1-funding-and-volatility-f16bed146b7d)
- [Hegic](https://www.hegic.co/) - Options with a liquidity pool
  - [Trade on v888](https://www.hegic.co/app.html)
  - [Trade on v1]((https://old.hegic.co/)
  - [v888 Whitepaper](https://www.hegic.co/assets/img/f833742b60c73b71520647d2594733b8.pdf)
  - [v1 Whitepaper](https://github.com/hegic/whitepaper/blob/master/Hegic%20Protocol%20Whitepaper.pdf)
  - [Whiteheart](https://www.whiteheart.finance/#/) - Onchain Hedging contracts using hegic
- [Dopex](https://www.dopex.io/) - Decentralized options pooled exchange on arbitrum
    - [Trade](https://app.dopex.io/ssov)
    - [Docs](https://docs.dopex.io/)
    - [Single Staking Vaults](https://docs.dopex.io/single-staking-options-vault-ssov)
    - [Curve Gauge War Options](https://blog.dopex.io/introducing-the-redacted-option-vaults-947ad9b03f9f?source=collection_home---6------0-----------------------)
- [Primitive](https://primitive.finance/) - Crypto Derivatives
Without Oracles
  - [Trade](https://rinkeby.app.primitive.finance/)
  - [Introducing Primitive](https://primitive.finance/blog/introducing-primitive)
  - [Docs](https://docs.primitive.finance/concepts/overview)
    - [RMM SDK](https://primitive.finance/blog/rmm-sdk)
    - [RMM Simulations](https://github.com/primitivefinance/rmms-py)
    - [RMM Examples](https://github.com/primitivefinance/rmm-examples)
  - [In depth Primitive Overview](https://twitter.com/__Thermopylae/status/1472319414288760837?s=20)
- [Premia](https://www.premia.finance/) - Options AMM
  - [Trade](https://app.premia.finance/)
  - [Docs](https://docs.premia.finance/)
  - [Premia volatility surface oracle](https://blog.premia.finance/premias-volatility-surface-oracle-b53adc259e72)
  - [Premia AMM](https://premia.finance/amm.pdf)
- [Opium](https://opium.finance/) - Trustless derivative contracts
  - [Docs](https://docs.opium.network/for-users/opium.finance)
- [Siren](https://siren.xyz/) - Polygon derivative trading with, leverage without liquidations
  - [Trade](https://app.siren.xyz/trade/)
  - [Siren V2](https://medium.com/siren-markets/siren-v2-brings-defi-options-trading-to-polygon-a5e051795342)
  - [Docs](https://docs.sirenmarkets.com/siren-protocol/glossary)
- [Pods](https://www.pods.finance/) - Options AMM
  - [Trade](https://app.pods.finance/)
  - [Docs](https://docs.pods.finance/)
  - [Whitepaper](https://www.pods.finance/pods_v1_whitepaper.pdf)
- [Vega](https://vega.xyz) - Derivative layer 1 based on tendermint
  - [Trade](https://vega.xyz/use/)
  - [Published Papers](https://vega.xyz/background#published-papers)
  - [Research Forum](https://community.vega.xyz/c/protocol-research-and-markets/24)
- [PsyOptions](https://www.psyoptions.io/) - Solana american style options
  - [Trade](https://trade.psyoptions.io/#/)
  - [Docs](https://docs.psyoptions.io/)

#### Futures

#### Perpetuals
##### Swaps
- zeta
- dydx
- perpetual protocol
- derivadex
- futureswap
- kine
- mango
- drift
- hubble

##### Options
- 01 protocol
- opyn

#### Interest Rate Swaps
- pendle
- element

#### Structured Products
- antimatter
- UXD
- Lemma

##### Option Vaults
- Ribbon
- Friktion
- Thetanuts
- StakeDAO
- Katana

#### Staking Derivatives
- lido
- metapool
- marinade
- stakewise
- rocketpool
- Solana native stake pool https://spl.solana.com/stake-pool

#### Other
- uma
- barnbridge
- volmex
- Thales
- kwenta
- qilin

## Research

### Option AMMs
- [Single-Sided Automated Market Maker for
European Options](https://www.pods.finance/pods_v1_whitepaper.pdf)
- [Hegic Whitepaper](https://github.com/hegic/whitepaper/blob/master/Hegic%20Protocol%20Whitepaper.pdf)
- [Dynamic Curves for Decentralized Autonomous Cryptocurrency Exchanges
](https://arxiv.org/abs/2101.02778)

#### Replicating Payoffs
- [Replicating Market Makers](https://stanford.edu/~guillean/papers/rmms.pdf)
- [The Replicating Portfolio of a Constant Product Market](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3550601)
- [The Replicating Portfolio of a Constant Product Market with Bounded Liquidity](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3898384)
- [Replicating Monotonic Payoffs Without Oracles](https://arxiv.org/abs/2111.13740)

#### Concentrated Liquidity and Option Payoffs
- [Uniswap V3 LP Tokens as Perpetual Put and Call Options](https://lambert-guillaume.medium.com/uniswap-v3-lp-tokens-as-perpetual-put-and-call-options-5b66219db827)
- [Pricing Uniswap v3 LP Positions: Towards a New Options Paradigm?](https://lambert-guillaume.medium.com/pricing-uniswap-v3-lp-positions-towards-a-new-options-paradigm-dce3e3b50125)
- [How to Create Perpetual Options in Uniswap v3](https://lambert-guillaume.medium.com/how-to-create-a-perpetual-options-in-uniswap-v3-3c40007ccf1)
- [Synthetic Options and Short Calls in Uniswap V3](https://lambert-guillaume.medium.com/synthetic-options-and-short-calls-in-uniswap-v3-a3aea5e4e273)

#### vAMMs
- [On vAMM's unnecessity for liquidity pool](https://github.com/Qmeasure/vAMM/blob/main/On%20vAMM's%20unnecessity%20for%20liquidity%20pool%20V1.1.pdf)
- [Perpetual Protocol Deep Dive into vAMM](https://medium.com/perpetual-protocol/a-deep-dive-into-our-virtual-amm-vamm-40345c522eeb)
- [Drift Dynamic AMM](https://docs.drift.trade/drift-dynamic-amm)
- [Drift dAMM Deep Dive](https://foregoing-script-fd0.notion.site/Drift-dAMM-deep-dive-ff154003aedb4efa83d6e7f4440cd4ab)
- [A reinforcement learning based approach to optimizing vAMMs](https://github.com/mystericalfox/working-docs/blob/main/A_reinforcement_learning_based_approach_to_optimizing_vAMMs.pdf)

### Power Perpetuals, Everlasting Options, and Perpetual Swaps
- [Cartoon Guide to Perps](https://research.paradigm.xyz/cartoon-guide-to-perps)
- [Everlasting Options](https://www.paradigm.xyz/2021/05/everlasting-options/)
- [Power Perpetuals](https://www.paradigm.xyz/2021/08/power-perpetuals/)  
- [Power Claims](https://github.com/waynenilsen/zendax/blob/master/latex/PowerClaims.pdf)
- [Raw Moments](https://llllvvuu.dev/blog/raw-moments)
- [Unbundling Gamma - ETH^2-PERP Proposal](https://llllvvuu.dev/blog/unbundling-gamma)
- [Floor Perps](https://www.paradigm.xyz/2021/08/floor-perps/)

### Other
- [A Protocol for Margining Derivatives](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3746200)
- [An automatic market maker with a dynamic repeg](https://curve.fi/files/crypto-pools-paper.pdf)

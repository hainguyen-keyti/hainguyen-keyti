### Keyti (Hai Nguyen)

<sup>Senior Smart Contract Engineer. 8 years building software.</sup>

---

I design and ship on-chain systems that hold real money. Live work includes a prediction game
settled in USDC on Arbitrum One, a Uniswap v4 hook AMM paired with an on-chain CLOB, and Move
contracts for a Sui launchpad audited by MoveBit. Contract code, test suites and deploy scripts
are published so anyone can read and audit them.

Contracts are the core of the work, but a product that holds real money needs more than contracts:
indexers that agree with the chain, gateways and admin surfaces, a deploy path that can be rolled
back, and monitors that catch a mismatch before a user does. I build those parts too, which is why
the contracts I write assume they will be operated, not just deployed.

---

**What I work on**

| | |
| --- | --- |
| **Contracts** | Solidity and Foundry. Uniswap v4 hooks, EIP-2535 Diamonds, ERC-4337 accounts, EIP-712 signed orders. Move on Sui. |
| **Cross-chain** | Bridge contracts, relayers, and the admin tooling around them. |
| **Backend** | TypeScript and NestJS services, PostgreSQL, Docker deploys. |
| **Indexing and data** | Event indexers and stats pipelines that recompute state from chain logs and reconcile it against the contracts. |
| **Frontend** | Next.js and React app and admin surfaces, with wagmi and viem on the chain side. |
| **Infrastructure** | RPC aggregation and failover, deploy and rollback paths, balance and health monitors on live money lanes. |
| **Automation** | Market-making bots, sweep and settlement scripts, agent tooling for my own workflow. |

---

**Currently working on**

- **[plinko-contracts](https://github.com/PrediX-Protocol/plinko-contracts)** Short-horizon ETH/USD prediction game, live on Arbitrum One and settled in USDC. Contracts, test suite and deploy scripts are published so the code can be read and audited.
- **[predix-contracts](https://github.com/PrediX-Protocol/predix-contracts)** PrediX V2, a Uniswap v4 hook AMM and an on-chain CLOB that share liquidity and route in a single transaction. On Unichain Sepolia, mainnet gated on external audit sign-off.
- **[plinko-stats](https://github.com/PrediX-Protocol/plinko-stats)** Stats recomputed from the game contract's own event logs, with no analytics vendor and no private database.
- **[yousui_contract](https://github.com/splabs-info/yousui_contract)** Move contracts for a launchpad on Sui covering IDO, INO and staking, audited by MoveBit.

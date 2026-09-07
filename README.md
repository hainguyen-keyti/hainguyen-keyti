### Keyti (Hai Nguyen)

Lead Smart Contract Engineer at SP Labs. I build on-chain systems that hold real money:
prediction markets, launchpads, and the settlement machinery under them.

**Working on now**

- **PrediX V2** ([predix-contracts](https://github.com/PrediX-Protocol/predix-contracts)): a
  prediction market where a Uniswap v4 hook AMM and an on-chain CLOB share the same liquidity
  and route in a single transaction. Live on Unichain Sepolia since April 2026, mainnet gated
  on external audit sign-off.
- **Plinko** ([plinko-contracts](https://github.com/PrediX-Protocol/plinko-contracts)): a
  short-horizon ETH/USD prediction game live on Arbitrum One, settled in USDC. Contracts, test
  suite and deploy scripts are public so the code can be read and audited. The
  [stats page](https://github.com/PrediX-Protocol/plinko-stats) is recomputed from the game
  contract's own event logs, with no analytics vendor and no private database.
- **YouSUI** ([yousui_contract](https://github.com/splabs-info/yousui_contract)): Move contracts
  for a launchpad on Sui covering IDO, INO and staking, audited by MoveBit.

**Stack**

Solidity, Foundry, Uniswap v4 hooks, EIP-2535 Diamonds, ERC-4337 account abstraction, EIP-712.
Move on Sui. TypeScript, NestJS, Postgres, Ponder indexers, Docker.

**How I work**

- Invariants first. The conservation properties a money system must never break are written down
  and encoded as tests before the feature exists, and every test is watched failing for the right
  reason before it is trusted passing.
- Numbers carry a method and a date. A figure nobody can reproduce does not go in a report.
- Builds are reproducible: dependencies vendored at exact revisions, no network access needed.

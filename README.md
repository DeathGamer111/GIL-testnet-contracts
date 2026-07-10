# GIL Testnet Contracts

![Gauss Gang](assets/gauss-gang.png)

Test tokens and NFT collections used for development and demonstrations on the Gauss Induction Labs (GIL) testnet. This repository is intended for non-production testing of Gauss token and NFT standards.

## Contents

- `contracts/` — test token and NFT contracts
- `hardhat.config.js` — Hardhat configuration
- `package.json` — development dependencies

## Development

```bash
npm install
npx hardhat compile
npx hardhat test
```

## Important

These contracts and associated test assets are for testnet use only. Do not treat testnet deployments, balances, or configuration as production-grade infrastructure.

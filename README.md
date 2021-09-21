# Rewards (RWD)

Rewards (RWD) is an Cross-Chain [ERC20](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md) / [BEP20](https://github.com/binance-chain/BEPs/blob/master/BEP20.md) token with additional functionality including minting and burning.

The total supply of the token is 210,770,198 and each token is divisible up to 18 decimal places.

## Details

- Name: Rewards
- Symbol: RWD
- Decimals: 18
- Deployments:
  - Ethereum Token (./contracts/RewardsToken.sol): [0xD80F72a6558ec337E0d4CF76b8752B17FA770860](https://etherscan.io/address/0xd80f72a6558ec337e0d4cf76b8752b17fa770860)
  - Binance Smart Chain Token (./contracts/BEP20Token.sol): [0x036BDd5bA9619ee0A895f8DC02867EBF453CB352](https://bscscan.com/address/0x036bdd5ba9619ee0a895f8dc02867ebf453cb352)
  - Ethereum Staking (./contracts/TokenFarm.sol): [0xc9cff883c4cf9258e0441e747f5cc71980f8fce6](https://etherscan.io/address/0xc9cff883c4cf9258e0441e747f5cc71980f8fce6)
  - Binance Smart Chain Staking (./contracts/TokenFarm.sol): [0x38e0f4167577cf73baf801100e466d2b363fb586](https://bscscan.com/address/0x38e0f4167577cf73baf801100e466d2b363fb586)
- Timelocks:
  - Team Timelock 1 (releaseTime Unix 1655265600): [0xC7997F523b536B8624Fd553B369500Cf13580CE7](https://etherscan.io/address/0xC7997F523b536B8624Fd553B369500Cf13580CE7)
  - Team Timelock 2 (releaseTime Unix 1686801600): [0x8d884f22c25Ca22481c84f9A797166b304577b50](https://etherscan.io/address/0x8d884f22c25Ca22481c84f9A797166b304577b50)
  - Team Timelock 3 (releaseTime Unix 1718424000): [0x51b90320ba8db0d0d2b8d62f0506cd85c0b90c68](https://etherscan.io/address/0x51b90320ba8db0d0d2b8d62f0506cd85c0b90c68)

## Installation

Add dependencies: Openzeppelin, Truffle, Hardhat.

```bash
npm install
```

## Flatten

```bash
npm run flat
```
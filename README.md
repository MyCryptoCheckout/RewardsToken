# Rewards (RWD)

Rewards (RWD) is an Bridged [ERC20](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md) / [BEP20](https://github.com/binance-chain/BEPs/blob/master/BEP20.md) token with additional functionality including minting and burning.

The max supply of the token is 500,000,000 and each token is divisible up to 18 decimal places.

## Details

- Name: Rewards
- Symbol: RWD
- Decimals: 18
- Deployments:
  - Ethereum Mainnet (./contracts/RewardsToken.sol): [0xD80F72a6558ec337E0d4CF76b8752B17FA770860] (https://etherscan.io/address/0xd80f72a6558ec337e0d4cf76b8752b17fa770860)
  - ERC20 Bridge : [0x06480810B00323BBBCF9f13901217386dd508dF7] (https://etherscan.io/address/0x06480810B00323BBBCF9f13901217386dd508dF7)
  - Binance Smart Chain Mainnet (./contracts/BEP20Token.sol): [0x036BDd5bA9619ee0A895f8DC02867EBF453CB352] (https://bscscan.com/address/0x036bdd5ba9619ee0a895f8dc02867ebf453cb352)
  - BEP20 Bridge : [0x036BDd5bA9619ee0A895f8DC02867EBF453CB352] (https://bscscan.com/address/0x036bdd5ba9619ee0a895f8dc02867ebf453cb352)

## Installation

```bash
npm install
```

## Flatten

For etherscan verification

```bash
npm run flatten
```
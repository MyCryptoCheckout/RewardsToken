# RewardsToken

The Rewards Token (RWD) is an [EIP20](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20-token-standard.md) token with additional functionality.

The total supply of the token is 100,000,000 and each token is divisible up to 18 decimal places.

## Details

- Deployments:
  - Ethereum Mainnet (./contracts/RewardsToken.sol)
- Decimals: 18
- Name: Rewards Token
- Symbol: RWD

## Installation

```bash
npm install
```

## Flatten

For etherscan verification

```bash
npx truffle-flattener ./contracts/RewardsToken.sol > ./contracts/RewardsTokenFlattened.sol
```

## remixd for remix IDE

To give the Remix IDE (the web app) access to a folder on your computer, you need to use Remixd -

```bash
npm install -g @remix-project/remixd
```

If your browser is on https://remix.ethereum.org (secure http) then use https in the command:

```bash
remixd -s <absolute-path-to-the-shared-folder> --remix-ide https://remix.ethereum.org
```
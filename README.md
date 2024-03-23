# Uniswap Labs Interface

## Zircuit integration

This fork of the Uniswap Interface is a custom version of the Uniswap Interface that integrates the Zircuit testnet.

## How to use this interface

First of all, you need to have a wallet that supports the Zircuit testnet. We recommend using MetaMask.To add the Zircuit testnet to MetaMask, follow these steps:

1. Open the [Zircuit.com](https://zircuit.com) and click on the "Connect Wallet" button.
2. Click on the "Add Network" button to add the Zircuit testnet to MetaMask.

After adding the Zircuit testnet to MetaMask, you can use this interface to interact with the Zircuit testnet.

To use this interface, visit [website](https://uniswap.ticton.xyz).

## How to deploy this interface

To deploy this interface, follow these steps:

1. Clone this repository.
2. Install the dependencies by running `yarn install`.
3. Before building the interface, you need to run the command `yarn prepare` to generate the necessary files.
4. Start the interface by running `yarn start`.

## Known issues

- The interface does not support lots of chains. If your wallet is connected to a chain that is not supported by the interface, you will not be able to use the interface. And It will show an error message.

- You may need to add token lists to the interface to see the tokens on the interface. You can create token lists by following the instructions in the [repo](https://github.com/skyline9981/token-list).

## Original information

An open source interface for Uniswap -- a protocol for decentralized exchange of Ethereum tokens.

- Website: [uniswap.org](https://uniswap.org/)
- Interface: [app.uniswap.org](https://app.uniswap.org)
- Docs: [uniswap.org/docs/](https://docs.uniswap.org/)
- Twitter: [@Uniswap](https://twitter.com/Uniswap)
- Reddit: [/r/Uniswap](https://www.reddit.com/r/Uniswap/)
- Email: [contact@uniswap.org](mailto:contact@uniswap.org)
- Discord: [Uniswap](https://discord.gg/FCfyBSbCU5)
- Whitepapers:
  - [V1](https://hackmd.io/C-DvwDSfSxuh-Gd4WKE_ig)
  - [V2](https://uniswap.org/whitepaper.pdf)
  - [V3](https://uniswap.org/whitepaper-v3.pdf)

## Accessing the Uniswap Interface

To access the Uniswap Interface, use an IPFS gateway link from the
[latest release](https://github.com/Uniswap/uniswap-interface/releases/latest),
or visit [app.uniswap.org](https://app.uniswap.org).

## Unsupported tokens

Check out `useUnsupportedTokenList()` in [src/state/lists/hooks.ts](./src/state/lists/hooks.ts) for blocking tokens in your instance of the interface.

You can block an entire list of tokens by passing in a tokenlist like [here](./src/constants/lists.ts) or you can block specific tokens by adding them to [unsupported.tokenlist.json](./src/constants/tokenLists/unsupported.tokenlist.json).

## Contributions

For steps on local deployment, development, and code contribution, please see [CONTRIBUTING](./CONTRIBUTING.md).

## Accessing Uniswap V2

The Uniswap Interface supports swapping, adding liquidity, removing liquidity and migrating liquidity for Uniswap protocol V2.

- Swap on Uniswap V2: https://app.uniswap.org/#/swap?use=v2
- View V2 liquidity: https://app.uniswap.org/#/pool/v2
- Add V2 liquidity: https://app.uniswap.org/#/add/v2
- Migrate V2 liquidity to V3: https://app.uniswap.org/#/migrate/v2

## Accessing Uniswap V1

The Uniswap V1 interface for mainnet and testnets is accessible via IPFS gateways
linked from the [v1.0.0 release](https://github.com/Uniswap/uniswap-interface/releases/tag/v1.0.0).

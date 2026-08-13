WHITEPAPER: USDG GOLD (USDG) — ERC-20 UTILITY TOKEN

1. OVERVIEW

This whitepaper defines the technical and functional specifications of USDG Gold (USDG), an independent blockchain-based digital utility token deployed on an EVM-compatible blockchain network using an ERC-20-style token architecture.

USDG Gold is designed for testing, community utility, decentralized application (dApp) integration, blockchain transactions, and ecosystem experimentation. The token operates independently and has no affiliation with Tether Limited or any other issuer of USDT.

The project focuses on transparent on-chain token mechanics, allowing users and compatible applications to interact with USDG through standard token functions such as transfers, approvals, and allowance-based transfers.

2. TOKEN SPECIFICATIONS

- Token Name: USDG Gold
- Token Symbol: USDG
- Contract Address: 0xAc381c1F6b4413de9D5E7dd8b2dFBf46971f268
- Network: Ethereum Mainnet / EVM-compatible network
- Token Standard: ERC-20-style
- Decimals: 18
- Total Supply: 10,000,000,000 USDG
- Supply Type: Fixed initial supply
- Token Type: Utility / Experimental Digital Asset

USDG Gold uses 18 decimal places, allowing token balances and transactions to be represented with high precision.

The total initial supply of USDG Gold is 10 billion tokens. The supply is established when the smart contract is deployed and the entire initial supply is assigned to the deploying address.

The contract does not include a public minting mechanism for creating additional USDG after deployment. Therefore, the token is designed around a fixed 10 billion USDG initial supply.

3. SMART CONTRACT & ARCHITECTURE

USDG Gold uses a Solidity-based smart contract implementing core ERC-20-style functionality.

The contract supports:
- Token transfers
- Token approvals
- Allowance-based transfers
- Balance tracking
- Total-supply tracking
- Ownership management
- Contract metadata URI
- Optional transfer constraints
- Recovery of unrelated ERC-20 tokens accidentally sent to the contract
- Recovery of native ETH accidentally sent to the contract

The token contract uses Solidity 0.8.20 and implements token accounting through balance and allowance mappings.

USDG Gold does not contain a public mint function, token tax mechanism, blacklist mechanism, or hidden balance-manipulation mechanism.

The contract also contains optional V2/V3 liquidity-pool transfer constraints. These restrictions can be enabled or disabled by the contract owner according to the deployed configuration.

4. TOKEN ECONOMICS

USDG Gold has a total supply of 10,000,000,000 USDG with 18 decimals.

The token is designed as a utility and experimental digital asset. Its supply and blockchain functionality should not be interpreted as representing ownership of physical gold, U.S. dollars, or any other underlying reserve unless separately documented by the project.

USDG Gold does not automatically possess a value of one U.S. dollar simply because its symbol or name contains "USDG."

The market value of the token, if any, is determined by the markets and applications in which it is voluntarily used or traded.

5. SECURITY & TRANSPARENCY

The smart contract provides on-chain visibility into token balances, transfers, approvals, ownership, and total supply.

Users can independently inspect blockchain transactions and contract information using compatible blockchain explorers.

The contract's ownership functionality allows the current owner to transfer ownership or renounce ownership. Administrative recovery functions are limited to the contract owner's ability to recover unrelated ERC-20 tokens or native ETH that may have been accidentally transferred to the contract.

The contract does not provide the owner with a function to arbitrarily transfer USDG from another user's wallet.

Users should always verify the official USDG Gold contract address before interacting with USDG Gold because token names and symbols are not unique on blockchain networks.

6. DISCLAIMER

USDG Gold (USDG) is an independent digital utility and experimental token. It is not issued, endorsed, sponsored, or affiliated with Tether Limited, Tether USD (USDT), or any other stablecoin issuer.

The token does not represent a claim on U.S. dollars, physical gold, bank deposits, government currency, or other assets unless explicitly established through separate legal and financial documentation.

The name "USDG Gold" and symbol "USDG" are used solely to identify this independent project and should not be interpreted as evidence of affiliation with another cryptocurrency or financial institution.

Users should independently evaluate the technical, economic, and legal risks before interacting with the token.

Always verify the official USDG Gold contract address before purchasing, transferring, or integrating the token into any wallet, exchange, or decentralized application.

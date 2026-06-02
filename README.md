# arc-crowdfund-mini

Refundable USDC crowdfunding on Arc testnet.

- Chain ID: `5042002`
- RPC: `https://rpc.testnet.arc.network`
- USDC: `0x3600000000000000000000000000000000000000`
- Explorer: https://testnet.arcscan.app

## Contract

`src/CrowdfundMini.sol` records USDC payments and emits accounting events.

## Build

```bash
forge build
```

## Deployment

- Contract: `0xB57a5C4B9984B4788DC3517854dF55F60B14bBB2`
- Tx: `inferred-from-nonce`
- Explorer: https://testnet.arcscan.app/address/0xB57a5C4B9984B4788DC3517854dF55F60B14bBB2

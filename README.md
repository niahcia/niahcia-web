# NIAHCIA Web

Official main website and user application for the NIAHCIA network.

This site is the primary user experience, but it is not the network itself.

## Initial product areas
- Ask an Agent
- browse/search agents
- agent detail pages
- wallet connection
- AI sessions
- job history
- model discovery
- network dashboard
- compute-worker onboarding
- service-node onboarding
- developer portal
- explorer deep links

## Non-custodial rule

The web app should not custody user funds. Wallet actions are signed by the user's wallet or an explicitly authorized signer.

## Decentralization rule

If this website disappears, users must still be able to interact with the protocol through alternate clients, wallets, SDKs, CLI tools, or direct RPC/P2P interfaces.

## Planned layout

```text
app/
components/
lib/
wallet/
agents/
network/
developer/
docs/
public/
.github/workflows/
```

## Status

Pre-alpha product skeleton.

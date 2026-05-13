# Overpass Docs

Documentation for Overpass, a Solana lending-pool tokenization and routing layer.

Overpass turns supported lending pools into redeemable, swappable SPL yield tokens. Minting deposits into the underlying source pool, and burning withdraws from it.

Public docs: https://docs.overpass.ag
Product site: https://overpass.ag

## Local preview

Install the Mintlify CLI and run the preview server from this directory:

```sh
npm i -g mint
mint dev
```

The docs site is configured in `docs.json`. Pages are MDX files.

## Structure

- `index.mdx` introduces Overpass.
- `quickstart.mdx` covers SDK setup and core flows.
- `concepts/` explains the asset model, minting, redemption, pricing, liquidity, and routing.
- `guides/` covers product workflows.
- `integrations/` covers SDK, aggregator, wallet, vault, treasury, and collateral integrations.
- `reference/` covers supported protocols, registry metadata, risk model, and program details.

## Validation

Check links before publishing:

```sh
mint broken-links
```

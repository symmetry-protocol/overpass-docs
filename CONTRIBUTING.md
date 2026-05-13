# Contribute to the Overpass docs

This repository contains the Mintlify documentation site for Overpass.

## Local development

1. Fork and clone this repository.
2. Install the Mintlify CLI: `npm i -g mint`.
3. Create a branch for your changes.
4. Edit the MDX files.
5. Run `mint dev` from the docs directory.
6. Preview your changes at `http://localhost:3000`.
7. Run `mint broken-links`.
8. Commit your changes and submit a pull request.

## Writing guidelines

- Use active voice.
- Address the reader directly with "you".
- Keep sentences concise.
- Lead with the user's goal.
- Use consistent Overpass terminology.
- Include concrete SDK examples when documenting integration flows.
- Make inherited source-pool risk explicit when discussing yield, routes, or withdrawals.

## Terminology

- Use "yield token" for the SPL token created by Overpass.
- Use "source pool" for the underlying lending pool or vault.
- Use "underlying asset" for the asset deposited into or redeemed from the source pool.
- Use "wrapper" when referring to the on-chain Overpass wrapper vault or SDK object.

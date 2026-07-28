# GitHub Repository Setup Checklist

Use this checklist when publishing the ChartUp promotional repository. This file can remain for maintainers or be omitted from the public repository after setup.

## Recommended Repository Settings

**Repository name**

Current: `solanavolumebot`

Recommended if renaming later: `chartup-volume-bot`

**Description**

> Official ChartUp hub for Solana, BNB, Robinhood Chain and Base testing tools, documentation and verified bot links.

**Homepage**

`https://www.chartup.io/`

**Topics**

`chartup`, `solana`, `solana-volume-bot`, `volume-bot`, `volume-booster`, `telegram-bot`, `blockchain-testing`, `developer-tools`, `bnb-chain`, `bnb-volume-bot`, `base`, `base-volume-bot`, `robinhood-chain`, `jito`, `raydium`, `pumpfun`, `meteora`

## Social Preview

Upload `assets/chartup-solana-volume-bot.jpg` under:

`Settings → General → Social preview`

GitHub may crop the image for different placements. Check the preview before saving.

## Repository Features

- Enable **Issues** for documentation corrections only.
- Disable **Projects** unless maintainers actively use a public project board.
- Keep **Discussions** disabled unless the support team will actively moderate them.
- Disable **Wiki** because the official GitBook is the canonical documentation source.
- Do not publish fake releases or packages for a repository that contains no software release.
- Do not label the repository open source.

## About Section

Add the official website and topics. Do not use unverified rankings, user counts, savings percentages, or performance guarantees in the About description.

## Branch Protection

For the default branch:

- Require a pull request before merging.
- Require at least one review when multiple maintainers are available.
- Block force pushes.
- Restrict direct changes to official links and security files.

## Ownership and Verification

- Publish from an organization or account clearly connected to ChartUp.
- Link the repository from `chartup.io` or an official ChartUp channel.
- Pin the repository if the account contains unrelated projects.
- Create a pinned issue reminding users that support never requests private keys or seed phrases.

## License Decision

Do not add an open-source software license unless ChartUp intentionally grants reuse rights. Public visibility alone does not require an OSI license. If documentation reuse is desired, obtain an authorized legal decision before adding a Creative Commons or software license.

## Final Pre-Publish Check

- Verify every Telegram username.
- Verify website, documentation, terms, and privacy links.
- Confirm current regional eligibility rules.
- Confirm current package and trial information.
- Render the README on GitHub and inspect tables, alerts, badges, and mobile layout.
- Run the included repository audit.

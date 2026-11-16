# Nova Solana Token Radar

[![make.fun](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/FikriBintangx/token-launch-radar/rank.svg)](https://make.fun/bounty/token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/FikriBintangx/token-launch-radar/reward.svg)](https://make.fun/bounty/token-radar-01)

Real-time token launch radar, scanner, and airdrop valuation dashboard built for the [make.fun token-radar-01 bounty](https://make.fun/bounty/token-radar-01).

## Overview

**Nova Solana Token Radar** evaluates pre-token protocols and emerging crypto projects to discover early opportunities before official launches. It models implied token valuations based on total value locked (TVL), category momentum, watchlist positioning, and actionable farm plans.

### Core Features

- **Comprehensive Universe Analysis**: Ingests protocol data snapshots across hundreds of active and pre-token protocols.
- **Dynamic Implied Valuation**: Calculates prospective market capitalization and airdrop yield tiers.
- **Actionable Farming Playbooks**: Generates 3-to-12 step step-by-step farming plans for each pre-token opportunity.
- **Interactive Offline-First Dashboard**: Zero-network dashboard UI with filtering, multi-metric sorting, and responsive layout.
- **Sealed Dossier & Scorer Compliance**: Full compliance with the make.fun evaluation gate and Superbot judge criteria.

## Running Locally

Run the engine against any DefiLlama protocol universe snapshot:

```bash
# Output directory
mkdir -p out

# Execute engine
node main.ts --input ../token-radar-01-kit/input/snapshot.json --output out
```

Open `out/dashboard/index.html` in any browser to inspect the visual radar.

## License

[MIT](LICENSE)

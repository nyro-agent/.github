<p align="center">
  <img src="https://raw.githubusercontent.com/nyro-agent/.github/main/profile/banner.jpg" alt="Nyro: every chain in, one USDC payout out" width="100%">
</p>

<h3 align="center">Mine on every chain. Collect it all in one place.</h3>

<p align="center">
  <a href="https://nyro.run">nyro.run</a> ·
  <a href="https://github.com/nyro-agent/nyro-agent">nyro-agent</a> ·
  <a href="https://www.npmjs.com/package/nyro-agent">npm</a>
</p>

**Nyro** is an AI mining agent. It reads your mining, staking and node payout wallets on **Solana, Ethereum, Base, Arbitrum, Polygon, Kaspa and Bitcoin**, prices every move with live LI.FI routes, holds what isn't worth the fees, and plans the rest into one **USDC** payout, on to your Robinhood deposit address.

```bash
npx -y nyro-agent web      # dashboard, harvest plan, terminal, settings on http://127.0.0.1:5550
```

| | |
|---|---|
| **Public addresses only** | Anything shaped like a private key or seed phrase is refused. |
| **You sign every step** | Each route is an unsigned transaction for your own wallet. Nyro never sends anything. |
| **Fees before moves** | Rewards under your minimum, or routes over your cost limit, are held. |
| **MCP server** | `scan_earnings`, `plan_harvest`, `get_transaction`, `get_settings`, `set_rules` for any AI agent. |

<sub>Not financial advice. MIT.</sub>

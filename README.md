# Agent Skills

A collection of skills for AI agents built with [OpenClaw](https://openclaw.ai).

Skills extend what your agent can do — each one is a focused, self-contained package with instructions, scripts, and references that teach an agent a new capability.

## Skills

### 🎯 [polymarket-monitor](./polymarket-monitor)

Monitor any [Polymarket](https://polymarket.com) prediction market and get alerted when odds cross a threshold.

**What it does:**
- Search for markets by topic (geopolitics, crypto, sports, elections — anything on Polymarket)
- Fetch live probabilities via the CLOB API (no API key needed)
- Set up a recurring cron job that alerts you on Slack when a market's Yes probability crosses your threshold

**Install:**
```bash
clawhub install polymarket-monitor
```

**Example usage:**
> "Monitor the chance of US strikes on Iran this month. Alert me if it hits 70%."

The agent finds the relevant markets, shows you current odds, and sets up the monitoring automatically.

---

## Installing Skills

Skills in this repo can be installed via [ClawHub](https://clawhub.com/xmeir-dev):

```bash
clawhub install <skill-name>
```

Or clone this repo and load directly into your agent workspace.

## Contributing

Found a bug or want to improve a skill? PRs welcome.

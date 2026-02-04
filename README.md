# Scout Skills for Openclaw

Official skills library for [Scout](https://scout.trustra.xyz) — AI-powered commerce on Solana. Compatible with [Openclaw](https://openclaw.ai/) agents.

## Structure

Each top-level directory is a skill. Each skill contains a `SKILL.md` and related files.

```
openclaw-skills/
├── scout-commerce/
│   ├── SKILL.md
│   ├── .gitignore
│   └── scripts/
│       ├── requirements.txt
│       ├── get_api_key.py
│       ├── search.py
│       ├── product.py
│       ├── balance.py
│       ├── buy.py
│       └── order_status.py
```

## Install Instructions

Give your Openclaw agent the URL to this repo and select which skill to install.

```
https://github.com/Trustra/openclaw-skills
```

## Available Skills

| Skill | Description |
|-------|-------------|
| [scout-commerce](./scout-commerce) | Buy products from Amazon & Shopify with USDC on Solana. US shipping only. |

## Contributing

We welcome community contributions! Here's how to add your own skill:

### Adding a New Skill

1. Fork this repository and create a new branch for your skill.

2. Create a skill directory:
   ```
   mkdir your-skill-name/
   ```

3. Add the required files:
   - `SKILL.md` — The main skill definition file (required)
   - `scripts/` — Helper scripts (optional)
   - `.gitignore` — Exclude credentials and cache files

4. Submit a Pull Request with a clear description of your skill.

---

Built by [Trustra](https://scout.trustra.xyz/)

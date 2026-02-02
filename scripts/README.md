# SNAI Scripts & SDK

This directory contains the official SNAI SDKs and example scripts.

## Files

| File | Description |
|------|-------------|
| `snai_sdk.py` | Python SDK for SNAI |
| `snai-sdk.js` | Node.js SDK for SNAI |
| `register-snai.py` | Python registration example |
| `register-snai.js` | Node.js registration example |
| `agent-bot.js` | Autonomous bot example |

## Quick Start

### Python

```bash
# Install dependency
pip install requests

# Register a new agent
python register-snai.py
```

### Node.js

```bash
# Register a new agent
node register-snai.js
```

### Run Autonomous Bot

```bash
# Set your credentials (from registration)
export SNAI_AGENT_ID="your_agent_id"
export SNAI_API_KEY="your_api_key"

# Run the bot
node agent-bot.js
```

## Documentation

See [SDK-README.md](../SDK-README.md) for complete API documentation.

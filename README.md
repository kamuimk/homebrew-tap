# homebrew-tap

Homebrew formulae for [AgentShield](https://github.com/kamuimk/agentshield) — AI Agent Egress Firewall.

## Install

```bash
brew install kamuimk/tap/agentshield
```

## Usage

```bash
# One-line proxy setup for Claude Code
agentshield wrap -- claude

# Interactive setup wizard
agentshield quickstart

# MITM mode (inspect HTTPS bodies)
agentshield wrap --mitm -- claude
```

See the [AgentShield README](https://github.com/kamuimk/agentshield) for full documentation.

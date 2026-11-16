# CapZero for Claude

Connect Claude to your CapZero organization: your installed apps, their records and the actions you're allowed to take. Your request directs the work. App guides are optional reference.

## Install

In Claude Code:

```sh
claude plugin marketplace add Upved-org/capzero-plugin
claude plugin install capzero@capzero
```

Then open `/mcp`, sign in to CapZero, choose your organization and allow the connection. No API key is copied.

In claude.ai, add CapZero as a custom connector with the URL `https://app.capzero.ai/mcp`.

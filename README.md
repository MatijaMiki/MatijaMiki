<img src="banner.svg" alt="" width="100%">

# hey, I'm Matija

Building **[ranwhat](https://ranwhat.com)**: a flight recorder for AI coding agents.

ranwhat reads what **Claude Code**, **Codex**, **Gemini CLI** and 17 other agents already ran on your machine, flags the risky actions, and finds the API keys they left in their transcripts. It runs locally, sends nothing, and is MIT licensed.

[![ranwhat repository](https://img.shields.io/badge/ranwhat-repository-ea8471?style=for-the-badge&logo=github&logoColor=white&labelColor=151B21)](https://github.com/MatijaMiki/ranwhat)
[![ranwhat.com website](https://img.shields.io/badge/ranwhat.com-website-ea8471?style=for-the-badge&labelColor=151B21)](https://ranwhat.com)
[![ranwhat on PyPI](https://img.shields.io/pypi/v/ranwhat?style=for-the-badge&logo=python&logoColor=white&label=pypi&labelColor=151B21&color=ea8471)](https://pypi.org/project/ranwhat/)
[![@ranwhatcom on X](https://img.shields.io/badge/@ranwhatcom-X-ea8471?style=for-the-badge&logo=x&logoColor=white&labelColor=151B21)](https://x.com/ranwhatcom)

## ranwhat

Thirty seconds, no signup:

```
uvx ranwhat check
```

| Command | What it answers |
| --- | --- |
| [`watch`](https://ranwhat.com/watch) | What did my agents run on this machine? |
| [`clean`](https://ranwhat.com/clean) | Which credentials are sitting in plaintext in their transcripts? |
| [`scan`](https://ranwhat.com/scan) | What can the tokens my agents hold actually do? |
| [`reach`](https://ranwhat.com/commands#reach) | Which MCP servers and credential files can they reach? |
| [`hook`](https://ranwhat.com/commands#hook) | Can it ask me before a high-risk call runs? |

## Guides

Practical AI agent security, each checked against the vendors' own documentation:

- [AI coding agent security: a checklist for your own machine](https://ranwhat.com/guides/ai-coding-agent-security)
- [Claude Code hooks for security: block risky tool calls](https://ranwhat.com/guides/claude-code-hooks-security)
- [How to stop Claude Code reading your .env file](https://ranwhat.com/guides/claude-code-env-secrets)
- [Prompt injection in coding agents](https://ranwhat.com/guides/prompt-injection-coding-agents)
- [An AI agent saw my API key. What now?](https://ranwhat.com/guides/rotate-leaked-api-key-ai-agent)

[All guides →](https://ranwhat.com/guides)

<img src="banner.svg" alt="" width="100%">

# hey, I'm Matija

Building **[ranwhat](https://ranwhat.com)**: a flight recorder for AI coding agents.

ranwhat reads what **Claude Code**, **Codex**, **Gemini CLI** and 17 other agents already ran on your machine, flags the risky actions, and finds the API keys they left in their transcripts. It runs locally, sends nothing, and is MIT licensed.

<p>
  <a href="https://github.com/MatijaMiki/ranwhat"><img src="pill-repo.svg" alt="ranwhat repository" height="48"></a>
  <a href="https://ranwhat.com"><img src="pill-site.svg" alt="ranwhat.com" height="48"></a>
  <a href="https://pypi.org/project/ranwhat/"><img src="pill-pypi.svg" alt="ranwhat on PyPI" height="48"></a>
  <a href="https://x.com/ranwhatcom"><img src="pill-x.svg" alt="@ranwhatcom on X" height="48"></a>
</p>

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

<img src="footer.svg" alt="" width="100%">

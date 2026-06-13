# Declaw

**Security-first sandboxing for AI agents.**

Declaw runs untrusted, AI-generated code in isolated [Firecracker](https://firecracker-microvm.github.io/) microVMs — hardware-level isolation with sub-second starts — and layers runtime security controls on top:

- 🔒 **MicroVM isolation** — every sandbox is a dedicated microVM, not a shared-kernel container
- 🌐 **Network policy enforcement** — per-sandbox egress filtering and domain allowlists
- 🛡️ **Built-in guardrails** — PII scanning, prompt injection defense, and toxicity detection
- 📝 **Audit logging** — full visibility into what your agents do
- ☁️ **Managed cloud or self-hosted** — run it as a service, or deploy in your own infrastructure

## SDKs & tools

| | |
|---|---|
| 🐍 **Python SDK** | [`declaw`](https://github.com/declaw-ai/declaw-python) · [PyPI](https://pypi.org/project/declaw/) |
| 📇 **TypeScript SDK** | [`@declaw/sdk`](https://github.com/declaw-ai/declaw-js) · [npm](https://www.npmjs.com/package/@declaw/sdk) |
| 🐹 **Go SDK** | [`declaw-go`](https://github.com/declaw-ai/declaw-go) |
| ⌨️ **CLI** | [`declaw-cli`](https://github.com/declaw-ai/declaw-cli) |
| 🔌 **MCP server** | [`mcp-server`](https://github.com/declaw-ai/mcp-server) — sandbox any MCP client |
| 🧩 **Integrations** | [n8n node](https://github.com/declaw-ai/n8n-nodes-declaw) · [Dify plugin](https://github.com/declaw-ai/dify-plugin) |

All SDKs and the CLI are open source under **Apache-2.0**.

## Links

- 🌍 Website: [declaw.ai](https://declaw.ai)
- 📚 Docs: [docs.declaw.ai](https://docs.declaw.ai)

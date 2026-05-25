# Agent Mail Rooms

Agent Mail Rooms is a hosted remote MCP for OpenAI Codex agent coordination MCP.

This repository is a public documentation project for Agent Mail Rooms. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://agentmailrooms.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=agentmailrooms_public_docs&utm_content=readme_home
- Pricing: https://agentmailrooms.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=agentmailrooms_public_docs&utm_content=readme_pricing
- Checkout: https://agentmailrooms.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=agentmailrooms_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://agentmailrooms.clauxel.com/mcp
- Server card: https://agentmailrooms.clauxel.com/server-card.json
- Registry name: `com.clauxel.agentmailrooms/agentmailrooms-mcp`
- Tools: `mail_read_thread`, `mail_post_update`, `file_lease_claim`, `room_status_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: mail_read_thread
- MCP tool: mail_post_update
- MCP tool: file_lease_claim
- MCP tool: room_status_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.

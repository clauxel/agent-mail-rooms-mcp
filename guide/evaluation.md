# Evaluation Guide

Use this page to evaluate whether Agent Mail Rooms fits a real workflow.

## What To Test

- OpenAI Codex agent coordination MCP
- Agent Mail Rooms
- Agent Mail Rooms documentation
- Agent Mail Rooms remote MCP
- agentmailrooms server card

## Expected Evidence

- Open Agent Mail Rooms and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://agentmailrooms.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call mail_read_thread with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://agentmailrooms.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=agentmailrooms_public_docs&utm_content=evaluation_checkout

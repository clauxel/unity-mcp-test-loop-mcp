# Evaluation Guide

Use this page to evaluate whether Unity MCP Test Loop fits a real workflow.

## What To Test

- Unity-MCP
- Unity MCP Test Loop
- Unity MCP Test Loop documentation
- Unity MCP Test Loop remote MCP
- unitymcptest server card

## Expected Evidence

- Open Unity MCP Test Loop and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://unitymcptest.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call run_unity_playmode_check with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: studio.

- https://unitymcptest.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=unitymcptest_public_docs&utm_content=evaluation_checkout

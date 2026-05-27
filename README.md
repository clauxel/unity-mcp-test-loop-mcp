# Unity MCP Test Loop

Unity MCP Test Loop is a hosted remote MCP for Unity-MCP.

This repository is a public documentation project for Unity MCP Test Loop. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://unitymcptest.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=unitymcptest_public_docs&utm_content=readme_home
- Pricing: https://unitymcptest.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=unitymcptest_public_docs&utm_content=readme_pricing
- Checkout: https://unitymcptest.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=unitymcptest_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://unitymcptest.clauxel.com/mcp
- Server card: https://unitymcptest.clauxel.com/server-card.json
- Registry name: `com.clauxel.unitymcptest/unitymcptest-mcp`
- Tools: `run_unity_playmode_check`, `invoke_unity_method`, `summarize_unity_failure`, `export_unity_receipt`

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
- MCP tool: run_unity_playmode_check
- MCP tool: invoke_unity_method
- MCP tool: summarize_unity_failure
- MCP tool: export_unity_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.

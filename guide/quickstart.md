# Quickstart

Unity MCP Test Loop is a hosted remote MCP for Unity-MCP.

## Fast Path

1. Open Unity MCP Test Loop and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://unitymcptest.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call run_unity_playmode_check with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://unitymcptest.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=unitymcptest_public_docs&utm_content=quickstart_home
- https://unitymcptest.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=unitymcptest_public_docs&utm_content=quickstart_pricing
- https://unitymcptest.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=unitymcptest_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://unitymcptest.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.

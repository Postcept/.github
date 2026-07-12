## Postcept

Proof-of-Completion for AI agents. Postcept checks that high-risk agent actions
(refunds, credits, cancellations, ticket updates) actually completed in the system
of record, then issues signed, tamper-evident receipts.

Postcept itself is a hosted product. What's open here is the trust layer and the API clients.

### Open source

[**receipt**](https://github.com/Postcept/receipt) ([`@postcept/receipt`](https://www.npmjs.com/package/@postcept/receipt)): verify a Postcept Receipt's signature yourself, in any JavaScript runtime. No API call, and nothing to trust but the published key.

[**sdk**](https://github.com/Postcept/sdk) ([`@postcept/sdk`](https://www.npmjs.com/package/@postcept/sdk)): typed TypeScript client for the API.

[**postcept-python**](https://github.com/Postcept/postcept-python) ([`postcept`](https://pypi.org/project/postcept/)): Python client for the API.

[**mcp**](https://github.com/Postcept/mcp) ([`@postcept/mcp`](https://www.npmjs.com/package/@postcept/mcp)): Model Context Protocol server, so an agent can verify its own actions as a tool.

[**relay**](https://github.com/Postcept/relay) ([`@postcept/relay`](https://www.npmjs.com/package/@postcept/relay)): Open-source customer-side relay for local connector credentials and evidence minimization.

[**demo**](https://github.com/Postcept/demo) ([`@postcept/demo`](https://www.npmjs.com/package/@postcept/demo)): Locally runnable CLI demo covering completion gap verification scenarios.

[**gauntlet**](https://github.com/Postcept/gauntlet) ([`@postcept/gauntlet`](https://www.npmjs.com/package/@postcept/gauntlet)): The Completion Gap Gauntlet, a reproducible scoring harness for verification baselines.

[**uptime**](https://github.com/Postcept/uptime): Independent, append-only uptime history.

### Links

[postcept.com](https://postcept.com) · [Docs](https://postcept.com/docs) · [The receipt standard](https://postcept.com/postcept-receipt) · [Security](https://postcept.com/security)

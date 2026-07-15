## Postcept

Outcome verification for action-taking AI agents. Postcept checks that high-risk
agent actions (refunds, credits, cancellations, ticket updates) actually completed
in the system of record, then issues signed, tamper-evident receipts and one
enforceable decision: safe to claim complete, or exactly why not.

Postcept itself is a hosted product at [postcept.com](https://postcept.com). What's open here is the trust layer and the API clients.

### Open source

[**receipt**](https://github.com/Postcept/receipt) ([`@postcept/receipt`](https://www.npmjs.com/package/@postcept/receipt)): verify a Postcept Receipt's signature yourself, in any JavaScript runtime. No API call, and nothing to trust but the published key.

[**sdk**](https://github.com/Postcept/sdk) ([`@postcept/sdk`](https://www.npmjs.com/package/@postcept/sdk)): typed TypeScript client for the API.

[**postcept-python**](https://github.com/Postcept/postcept-python) ([`postcept`](https://pypi.org/project/postcept/)): Python client for the API.

[**mcp**](https://github.com/Postcept/mcp) ([`@postcept/mcp`](https://www.npmjs.com/package/@postcept/mcp)): Model Context Protocol server, so an agent can verify its own actions as a tool.

[**relay**](https://github.com/Postcept/relay) ([`@postcept/relay`](https://www.npmjs.com/package/@postcept/relay)): customer-side relay. Credentials and raw records stay in your environment, Postcept receives a signed observation.

[**gauntlet**](https://github.com/Postcept/gauntlet) ([`@postcept/gauntlet`](https://www.npmjs.com/package/@postcept/gauntlet)): reproducible broken-refund scenarios scored against the live engine and public baselines.

[**uptime**](https://github.com/Postcept/uptime): independent uptime history, probed every 15 minutes from infrastructure outside the accounts that serve the API.

### Verify us

Every receipt is offline-verifiable against the published key, log checkpoints are witnessed on Sigstore Rekor, and the [status page](https://postcept.github.io/uptime/) regenerates from a public probe history.

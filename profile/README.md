# Postcept

**Proof-of-Completion for AI agents.**

When an AI agent says it issued a refund, cancelled a subscription, or resolved a
ticket, that is a claim, not proof. Postcept checks the claim against the system of
record (Stripe, Zendesk, and others), catches false or duplicate completion, and
issues a signed receipt anyone can verify.

### Open source

- **[receipt](https://github.com/Postcept/receipt)** &nbsp;`npm i @postcept/receipt`
  <br>The reference verifier. Check a receipt's Ed25519 signature and its place in the
  transparency log, in Node, the browser, Deno, or an edge runtime.
- **[sdk](https://github.com/Postcept/sdk)** &nbsp;`npm i @postcept/sdk`
  <br>Typed TypeScript client for the API.
- **[postcept-python](https://github.com/Postcept/postcept-python)** &nbsp;`pip install postcept`
  <br>Python client for the API.
- **[mcp](https://github.com/Postcept/mcp)** &nbsp;`npx @postcept/mcp`
  <br>Model Context Protocol server, so an agent can verify its own actions as a tool.

Product at [postcept.com](https://postcept.com). Docs at [postcept.com/docs](https://postcept.com/docs).

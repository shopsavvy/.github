# Security policy

This policy covers every public repository in the [ShopSavvy GitHub organization](https://github.com/shopsavvy) (the SDKs, the MCP server and the integrations) and the services they call: the ShopSavvy Data API at `api.shopsavvy.com` and the hosted MCP server at `api.shopsavvy.com/mcp`.

## Reporting a vulnerability

Email **support@shopsavvy.com** with "Security" in the subject. Please do not open a public issue, discussion or pull request for a vulnerability.

Include:

- what is affected (repository and version, or the API endpoint)
- how to reproduce it, and what an attacker could do with it
- any request IDs (`meta.request_id` in API responses) and timestamps

We will acknowledge your report, keep you updated while we investigate, and tell you when it is fixed. Please give us a reasonable time to fix the issue before disclosing it publicly.

## Leaked API keys

If you find a ShopSavvy API key (`ss_live_...`) in a public place, report it to the same address. If it is your own key, revoke it right away at [shopsavvy.com/data/api-keys](https://shopsavvy.com/data/api-keys) and create a new one.

## Supported versions

Security fixes go into the latest release of each SDK and of the MCP server package. Upgrade to the latest version to receive them.

## Out of scope

- Rate limiting and credit accounting working as documented
- Reports from automated scanners without a demonstrated impact
- Social engineering of ShopSavvy staff or users

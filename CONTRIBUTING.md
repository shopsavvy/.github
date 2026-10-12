# Contributing

Thanks for helping improve ShopSavvy's open-source SDKs, MCP server and integrations. Repositories with their own CONTRIBUTING.md follow that file; this is the default for the rest.

1. **Open an issue first** for anything bigger than a small fix, so we can agree on the approach.
2. **Keep the SDKs in step with the API.** Field names match the API JSON, and new endpoints or fields follow the [API docs](https://shopsavvy.com/data/documentation) and [OpenAPI spec](https://api.shopsavvy.com/v1/openapi.json). Don't add endpoints or fields the API doesn't have.
3. **Tests run offline.** Mock HTTP with recorded fixtures and obviously fake keys (`ss_test_...`). Run the repository's test command before opening a pull request (each repo's README or AGENTS.md lists it).
4. **Never commit an API key, token or password**, including in examples, fixtures or build config. Examples read the key from `SHOPSAVVY_API_KEY`.
5. **One change per pull request**, with a description of what changed and why.

By contributing you agree that your contribution is licensed under the repository's license (MIT for the SDKs and the MCP server), and you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

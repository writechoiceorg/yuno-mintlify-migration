# Yuno Documentation Project Instructions

## About this project

- This is Yuno's payment API documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- API reference pages use OpenAPI spec at `api-reference/openapi.json`
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "checkout session" (not "session" alone)
- Use "payment method" (not "payment type" in prose)
- Use "provider" (not "gateway" or "acquirer" unless specifically referring to those)
- Use "Dashboard" (capitalized) when referring to the Yuno Dashboard
- Use "sandbox" (lowercase) for the test environment
- Use "merchant" for API consumers

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, API fields, and code references
- Always include the full API header names: `public-api-key`, `private-secret-key`, `account-code`

## Content boundaries

- Document only Yuno ecosystem features and APIs
- Do not reference competitor payment platforms
- Do not document internal admin features or Yuno-internal tooling
- Sensitive data (API keys, merchant IDs) in examples must use placeholder values

---
name: Get a delayed global stock quote
description: Look up a delayed quote for an equity on any global exchange via the Xignite Global Quotes
  API.
api: openapi/xignite-xigniteglobalquotes-api-openapi.yml
operations:
- GET /v3/xGlobalQuotes/ListExchanges
- GET /v3/xGlobalQuotes/ListSymbols
- GET /v3/xGlobalQuotes/GetGlobalDelayedQuote
generated: '2026-07-22'
method: generated
---

# Get a delayed global stock quote

Base URL: `https://globalquotes.xignite.com`

1. Authenticate every request with the account token as a query parameter: `?_token=<token>`. There is no OAuth; the scheme is an apiKey named `_token` in the query string (see `authentication/xignite-authentication.yml`).
2. If you do not know the exchange code, call `GET /v3/xGlobalQuotes/ListExchanges` to list supported exchanges, and `GET /v3/xGlobalQuotes/ListSymbols?Exchange=<code>` to find the symbol on that exchange.
3. Fetch the quote with `GET /v3/xGlobalQuotes/GetGlobalDelayedQuote`, identifying the instrument with an exchange-qualified symbol (for example `IBM.XNYS`). Use `GET /v3/xGlobalQuotes/GetGlobalDelayedQuotes` for a batched multi-symbol request.
4. Check the in-band envelope on every response: HTTP status is always 200; success means `Outcome: Success`. `RequestError` means a bad symbol/parameter (fix the request), `RegistrationError` means an invalid or unentitled `_token`, `SystemError` is provider-side (retry later). The `Message` field explains the failure (see `errors/xignite-problem-types.yml`).

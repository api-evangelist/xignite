---
name: Get a real-time FX rate and convert an amount
description: Fetch a live foreign-exchange rate and convert a monetary amount between currencies with
  the Xignite Global Currencies API.
api: openapi/xignite-xigniteglobalcurrencies-api-openapi.yml
operations:
- GET /xGlobalCurrencies/ListActiveCurrencies
- GET /xGlobalCurrencies/GetRealTimeRate
- GET /xGlobalCurrencies/ConvertRealTimeValue
generated: '2026-07-22'
method: generated
---

# Get a real-time FX rate and convert an amount

Base URL: `https://globalcurrencies.xignite.com`

1. Authenticate with `?_token=<token>` on every request (apiKey in query; no OAuth).
2. Optionally call `GET /xGlobalCurrencies/ListActiveCurrencies` to confirm both currencies are supported.
3. For the rate alone, call `GET /xGlobalCurrencies/GetRealTimeRate` with the currency pair symbol (for example `EURUSD`). For a converted amount, call `GET /xGlobalCurrencies/ConvertRealTimeValue` with the pair and the amount to convert; use `GET /xGlobalCurrencies/ConvertHistoricalValue` for an as-of-date conversion.
4. Note these currency operations are unversioned paths (no `/v3/` prefix), unlike most other Xignite services.
5. Treat `Outcome: Success` as the success signal (HTTP is always 200); on `RequestError` check the pair symbol, on `RegistrationError` check the token/entitlement (see `errors/xignite-problem-types.yml`).

---
name: Pull historical prices and dividend history
description: Retrieve an end-of-day price series and cash dividend history for an equity with the Xignite
  Global Historical API.
api: openapi/xignite-xigniteglobalhistorical-api-openapi.yml
operations:
- GET /v3/xGlobalHistorical/GetGlobalHistoricalQuotesRange
- GET /v3/xGlobalHistorical/GetCashDividendHistory
- GET /v3/xGlobalHistorical/GetAdjustmentFactors
generated: '2026-07-22'
method: generated
---

# Pull historical prices and dividend history

Base URL: `https://globalhistorical.xignite.com`

1. Authenticate with `?_token=<token>` on every request (apiKey in query; no OAuth).
2. Pull the price series with `GET /v3/xGlobalHistorical/GetGlobalHistoricalQuotesRange`, passing the exchange-qualified symbol and a start/end date range. Weekly, monthly, and quarterly variants exist (`GetGlobalHistoricalWeeklyQuotesRange`, `GetGlobalHistoricalMonthlyQuotesRange`, `GetGlobalHistoricalQuarterlyQuotesRange`).
3. Fetch dividends with `GET /v3/xGlobalHistorical/GetCashDividendHistory` and splits with `GET /v3/xGlobalHistorical/GetSplitHistory` for the same symbol.
4. To adjust the raw price series for corporate actions, fetch `GET /v3/xGlobalHistorical/GetAdjustmentFactors` and apply the factors to the price rows.
5. Every response is HTTP 200 with the `Outcome`/`Message` envelope — only `Outcome: Success` is a success (see `errors/xignite-problem-types.yml`).

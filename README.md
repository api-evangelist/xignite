# Xignite (xignite)

Xignite pioneered cloud-based financial market data APIs, offering a catalog of 40+ REST web services covering equities, forex, crypto, indices, options, futures, fixed income, mutual funds, corporate actions, news, ESG, and reference data. Each API lives on its own subdomain (for example globalquotes.xignite.com) and returns JSON, XML, or CSV, with bulk datasets delivered as files via CloudFiles and streaming quotes via its CloudStreaming product. Founded in 2000, Xignite was acquired by QUODD (a NewSpring Holdings company) in February 2023; the xignite.com developer catalog remains live while corporate pages redirect to quodd.com, and QUODD runs a newer developer platform at developer.quodd.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/xignite/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/xignite/refs/heads/main/apis.yml)

## Tags

- Financial
- Market Data
- Stocks
- Real-Time
- Forex
- Cryptocurrency
- Options
- Futures
- Fixed Income
- Reference Data
- Corporate Actions
- Mutual Funds
- ESG
- News

## Timestamps

- **Created:** 2026-07-21
- **Modified:** 2026-07-21

## APIs

### Xignite Global Quotes API

Delayed stock quotes for equities across global exchanges, served as REST operations (GetGlobalDelayedQuote, symbol changes, chart bars) in JSON, XML, or CSV from the globalquotes.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/global-stock-quote-data/](https://www.xignite.com/product/global-stock-quote-data/)
- **Base URL:** `https://globalquotes.xignite.com`

#### Tags

- Stocks
- Quotes
- Delayed

#### Properties

- [Documentation](https://www.xignite.com/product/global-stock-quote-data/)
- [OpenAPI](openapi/xignite-global-quotes-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Real-Time API

Real-time stock quote data for global equities via REST request/response operations on the globalrealtime.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/global-real-time-stock-quote-data/](https://www.xignite.com/product/global-real-time-stock-quote-data/)
- **Base URL:** `https://globalrealtime.xignite.com`

#### Tags

- Stocks
- Real-Time
- Quotes

#### Properties

- [Documentation](https://www.xignite.com/product/global-real-time-stock-quote-data/)
- [OpenAPI](openapi/xignite-global-real-time-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Historical API

End-of-day and historical equity prices including historical quote ranges, chart bars, adjustment factors, and cash dividend history from the globalhistorical.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/historical-stock-prices/](https://www.xignite.com/product/historical-stock-prices/)
- **Base URL:** `https://globalhistorical.xignite.com`

#### Tags

- Stocks
- Historical
- End of Day

#### Properties

- [Documentation](https://www.xignite.com/product/historical-stock-prices/)
- [OpenAPI](openapi/xignite-global-historical-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Currencies API

Real-time, historical, and average foreign exchange rates - one of Xignite's longest-running and most widely used APIs - served from the globalcurrencies.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/forex/](https://www.xignite.com/product/forex/)
- **Base URL:** `https://globalcurrencies.xignite.com`

#### Tags

- Forex
- Currencies
- Exchange Rates

#### Properties

- [Documentation](https://www.xignite.com/product/forex/)
- [OpenAPI](openapi/xignite-global-currencies-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Metals API

Spot prices, bars, and historical rates for precious metals such as gold, silver, platinum, and palladium from the globalmetals.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/gold-metal/](https://www.xignite.com/product/gold-metal/)
- **Base URL:** `https://globalmetals.xignite.com`

#### Tags

- Metals
- Gold
- Commodities

#### Properties

- [Documentation](https://www.xignite.com/product/gold-metal/)
- [OpenAPI](openapi/xignite-global-metals-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Crypto API

Cryptocurrency market data including quotes, chart bars, and historical prices for digital assets from the crypto.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/cryptocurrency-api/](https://www.xignite.com/product/cryptocurrency-api/)
- **Base URL:** `https://crypto.xignite.com`

#### Tags

- Crypto
- Cryptocurrency
- Digital Assets

#### Properties

- [Documentation](https://www.xignite.com/product/cryptocurrency-api/)
- [OpenAPI](openapi/xignite-crypto-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Indices API

Stock market index and benchmark values with chart bars and index metadata from the globalindices.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/index-values/](https://www.xignite.com/product/index-values/)
- **Base URL:** `https://globalindices.xignite.com`

#### Tags

- Indices
- Benchmarks
- Index Values

#### Properties

- [Documentation](https://www.xignite.com/product/index-values/)
- [OpenAPI](openapi/xignite-global-indices-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Options API

Option price data including quotes and chains for listed equity options from the globaloptions.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/global-option-price-data/](https://www.xignite.com/product/global-option-price-data/)
- **Base URL:** `https://globaloptions.xignite.com`

#### Tags

- Options
- Derivatives
- Prices

#### Properties

- [Documentation](https://www.xignite.com/product/global-option-price-data/)
- [OpenAPI](openapi/xignite-global-options-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Futures API

Futures contract prices and metadata across commodity, index, and financial futures from the globalfutures.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/XigniteGlobalFutures/](https://www.xignite.com/product/XigniteGlobalFutures/)
- **Base URL:** `https://globalfutures.xignite.com`

#### Tags

- Futures
- Derivatives
- Commodities

#### Properties

- [Documentation](https://www.xignite.com/product/XigniteGlobalFutures/)
- [OpenAPI](openapi/xignite-global-futures-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Bonds API

Bond price data for fixed income securities from the bonds.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/bond-prices/](https://www.xignite.com/product/bond-prices/)
- **Base URL:** `https://bonds.xignite.com`

#### Tags

- Bonds
- Fixed Income
- Prices

#### Properties

- [Documentation](https://www.xignite.com/product/bond-prices/)
- [OpenAPI](openapi/xignite-bonds-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Money Markets API

Money market, treasury, swap, and interbank rate data from the moneymarkets.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/swaps-treasuries-data/](https://www.xignite.com/product/swaps-treasuries-data/)
- **Base URL:** `https://moneymarkets.xignite.com`

#### Tags

- Rates
- Treasuries
- Swaps

#### Properties

- [Documentation](https://www.xignite.com/product/swaps-treasuries-data/)
- [OpenAPI](openapi/xignite-money-markets-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Master API

Global security master and reference data - symbology, listings, identifiers, and instrument metadata - from the globalmaster.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/global-security-master-data/](https://www.xignite.com/product/global-security-master-data/)
- **Base URL:** `https://globalmaster.xignite.com`

#### Tags

- Reference Data
- Security Master
- Symbology

#### Properties

- [Documentation](https://www.xignite.com/product/global-security-master-data/)
- [OpenAPI](openapi/xignite-global-master-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Corporate Actions API

Corporate action events such as dividends, splits, mergers, and symbol changes from the globalcorporateactions.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/XigniteGlobalCorporateActions/](https://www.xignite.com/product/XigniteGlobalCorporateActions/)
- **Base URL:** `https://globalcorporateactions.xignite.com`

#### Tags

- Corporate Actions
- Dividends
- Splits

#### Properties

- [Documentation](https://www.xignite.com/product/XigniteGlobalCorporateActions/)
- [OpenAPI](openapi/xignite-global-corporate-actions-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global News API

Company financial news headlines, market summaries, and press release data from the globalnews.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/company-financial-news/](https://www.xignite.com/product/company-financial-news/)
- **Base URL:** `https://globalnews.xignite.com`

#### Tags

- News
- Headlines
- Companies

#### Properties

- [Documentation](https://www.xignite.com/product/company-financial-news/)
- [OpenAPI](openapi/xignite-global-news-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Earnings Calendar API

Company earnings announcement dates and earnings calendar data from the earningscalendar.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/earnings-calendar-data/](https://www.xignite.com/product/earnings-calendar-data/)
- **Base URL:** `https://earningscalendar.xignite.com`

#### Tags

- Earnings
- Calendar
- Events

#### Properties

- [Documentation](https://www.xignite.com/product/earnings-calendar-data/)
- [OpenAPI](openapi/xignite-earnings-calendar-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite NAVs API

Mutual fund net asset values (NAVs), adjustment factors, and fund pricing history from the navs.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/mutual-fund-NAVs/](https://www.xignite.com/product/mutual-fund-NAVs/)
- **Base URL:** `https://navs.xignite.com`

#### Tags

- Mutual Funds
- NAV
- Funds

#### Properties

- [Documentation](https://www.xignite.com/product/mutual-fund-NAVs/)
- [OpenAPI](openapi/xignite-navs-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Fund Fundamentals API

Fund fundamental data - holdings, performance, and profile details for mutual funds and ETFs - from the globalfundfundamentals.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/global-fund-market-data/](https://www.xignite.com/product/global-fund-market-data/)
- **Base URL:** `https://globalfundfundamentals.xignite.com`

#### Tags

- Funds
- Fundamentals
- Mutual Funds

#### Properties

- [Documentation](https://www.xignite.com/product/global-fund-market-data/)
- [OpenAPI](openapi/xignite-global-fund-fundamentals-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite FactSet Fundamentals API

Company fundamentals and financial statement data sourced from FactSet, served from the factsetfundamentals.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/factset-fundamentals-financials/](https://www.xignite.com/product/factset-fundamentals-financials/)
- **Base URL:** `https://factsetfundamentals.xignite.com`

#### Tags

- Fundamentals
- Financials
- FactSet

#### Properties

- [Documentation](https://www.xignite.com/product/factset-fundamentals-financials/)
- [OpenAPI](openapi/xignite-factset-fundamentals-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global ESG API

Environmental, social, and governance (ESG) data for companies from the globalesg.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/esg-api/](https://www.xignite.com/product/esg-api/)
- **Base URL:** `https://globalesg.xignite.com`

#### Tags

- ESG
- Sustainability
- Ratings

#### Properties

- [Documentation](https://www.xignite.com/product/esg-api/)
- [OpenAPI](openapi/xignite-global-esg-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite Global Holidays API

Exchange trading hours, market holidays, and calendar data for global exchanges from the globalholidays.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/exchange-hours-calendars/](https://www.xignite.com/product/exchange-hours-calendars/)
- **Base URL:** `https://globalholidays.xignite.com`

#### Tags

- Exchanges
- Holidays
- Calendars

#### Properties

- [Documentation](https://www.xignite.com/product/exchange-hours-calendars/)
- [OpenAPI](openapi/xignite-global-holidays-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite CloudAlerts API

Market event alerting - create and manage alerts on market data conditions - from the alerts.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/market-data-alerts/](https://www.xignite.com/product/market-data-alerts/)
- **Base URL:** `https://alerts.xignite.com`

#### Tags

- Alerts
- Events
- Notifications

#### Properties

- [Documentation](https://www.xignite.com/product/market-data-alerts/)
- [OpenAPI](openapi/xignite-cloud-alerts-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Xignite CloudStreaming API

Streaming product for pushing real-time quotes directly to applications. The product page is live but transport details (protocol, endpoints) are only documented behind registration; no public spec was found, so none is included here.

- **Human URL:** [https://www.xignite.com/product/CloudStreaming/](https://www.xignite.com/product/CloudStreaming/)

#### Tags

- Streaming
- Real-Time
- Quotes

#### Properties

- [Documentation](https://www.xignite.com/product/CloudStreaming/)

### Xignite CloudFiles API

Bulk file delivery service behind Xignite's file products (historical equity prices, bonds, options, currencies, and corporate actions files), served from the cloudfiles.xignite.com service.

- **Human URL:** [https://www.xignite.com/product/historical-equities-prices-file/](https://www.xignite.com/product/historical-equities-prices-file/)
- **Base URL:** `https://cloudfiles.xignite.com`

#### Tags

- Files
- Bulk Data
- Downloads

#### Properties

- [Documentation](https://www.xignite.com/product/historical-equities-prices-file/)
- [OpenAPI](openapi/xignite-cloud-files-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://www.quodd.com/)
- [Portal](https://www.xignite.com/developers)
- [Documentation](https://developer.quodd.com/)
- [GitHub Organization](https://github.com/Xignite)
- [LinkedIn](https://www.linkedin.com/company/quodd)
- [Blog](https://quodd.com/insights)
- [Sign Up](https://www.xignite.com/xignite-trial)
- [Terms of Service](https://quodd.com/terms-of-use)
- [Privacy Policy](https://quodd.com/privacy-policy)
- [Support](https://quodd.com/support)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

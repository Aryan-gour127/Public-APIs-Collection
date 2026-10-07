# Finance APIs

## Frankfurter

- **Type:** Currency and foreign-exchange rates
- **Authentication:** No API key
- **Access:** Free and open source
- **Data:** Daily rates from central banks and other official sources; supports current, historical, and time-series queries.
- **API:** `https://api.frankfurter.dev`
- **Documentation:** [Frankfurter docs](https://www.frankfurter.app/)
- **Example:** `GET https://api.frankfurter.dev/v2/rates?base=usd&quotes=eur,gbp`

## ExchangeRate-API Open Access

- **Type:** Currency and foreign-exchange rates
- **Authentication:** No key for the Open Access endpoint
- **Access:** Free; daily updates and rate limits apply. Attribution is required, and redistribution is not allowed by its terms.
- **API:** `https://open.er-api.com/v6/latest/USD`
- **Documentation and terms:** [Open Access docs](https://www.exchangerate-api.com/docs/free)

ExchangeRate-API also offers a separate key-based Free plan (1,500 requests/month) and paid plans. Check the provider's site for current quotas and pricing.

## CoinGecko

- **Type:** Cryptocurrency market data
- **Authentication:** API key for Demo and paid API plans
- **Free:** Demo plan is $0, with 10,000 calls/month and a 100 calls/minute limit as listed by the provider.
- **Paid:** Basic is listed at $35/month when billed yearly, with 100,000 calls/month and a 300 calls/minute limit. Higher tiers are available.
- **Documentation:** [API docs](https://docs.coingecko.com/) · [Plans and pricing](https://www.coingecko.com/en/api/pricing)

Plan prices and limits may change. Check the official pricing page before selecting a plan.

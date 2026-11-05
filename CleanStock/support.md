---
title: Clean Stock Support
permalink: /CleanStock/support/
---

# Clean Stock Support

Clean Stock is built to keep market tracking calm and focused. If something is not working as expected, contact us at [civetworks@outlook.com](mailto:civetworks@outlook.com).

## Common Questions

### How do I add a ticker?

Tap the plus button, search by ticker or company/fund name, then add the result to a list.

### How do I delete a ticker?

Long-press a ticker row on the home screen and choose Delete.

### How do I rename a list?

Double-tap the list name at the top of the home screen, enter the new name, then finish editing.

### Why is a ticker missing data?

Some symbols, markets, or funds may have incomplete quote, chart, holdings, comparison, or news data depending on provider availability. Check your connection and try again later. A missing value does not mean the value is zero.

### When will I see a pre-market or post-market price?

In version 1.11 or later, stock and ETF watchlists and the 1D detail chart can show trades in the hour before the regular open or the hour after the regular close. The hours follow the asset's exchange. A trade from that day's window must be available. At other times you'll see the regular-session quote and its date.

On the 1D chart, tap Pre-market or Post-market to see the regular Market price, date and daily change. Tap Market to switch back. Watchlist rows use a lighter percentage badge for extended-hours quotes. Pre-market change is measured from the last completed session's close. Post-market change is measured from the prior trading day's close. Paper Trading and price alerts use regular-session quotes.

### How do I compare price change and total return?

Open a stock, choose Performance, and scroll to Benchmark. In version 1.11 or later, tap Price or Total Return above the chart. Price uses closing prices, while Total Return uses adjusted closing prices when available. Tap the benchmark ticker (SPY by default) to choose a comparison.

### Why is Sentiment missing or unavailable?

Open a stock or ETF, scroll below the chart and statistics, and select Sentiment.

In version 1.11 or later, Sentiment requires iOS 27 or later and an iPhone eligible for Apple Private Cloud Compute (PCC). It is hidden on iOS 26 and on devices Apple reports as ineligible for PCC. Availability also depends on your region and system settings.

On an eligible iPhone, check Apple Intelligence in Settings and your network connection. A temporary setup or service issue keeps the Sentiment entry visible. If the daily PCC quota has been reached, the app shows the reset time when Apple provides it. Try again when the service is available.

### Where does Sentiment analysis run?

From version 1.11, Apple Private Cloud Compute generates every new Sentiment report. Creating a report requires a connection to Apple. The request includes the selected asset's news, market data, available company or fund information, and optional retrieved web excerpts. Personal holding quantities, paper trades, notes, and the full watchlist are excluded. Summaries can be incorrect.

### How do I enable broader web research?

On iOS 27 or later, open Settings → Web Research and save your own [Tavily API key](https://app.tavily.com/) and/or [Brave Search API key](https://api-dashboard.search.brave.com/). Tavily is preferred; Brave can provide backup search or work on its own. The overview researches events, financials, risks and industry, then can investigate specific gaps. Search excerpts are used first; reading Yahoo or publisher articles when needed requires Tavily. The App connects directly to the providers, with no server setup. Saving a key does not test it or make a request.

Each analysis permits up to six search requests and two article reads across provider fallback and context retries. Cache hits do not spend a request. Your provider plans, limits and charges apply. A missing or rejected key, rate limit or unreadable page preserves the available evidence and adds an explanation. Coverage varies by asset and publisher.

Each key stays in this device's Keychain and is not sent to the model. Remove Key disables that provider for future analyses. To change a key, remove it before adding another. Without any search key, Sentiment uses the available Yahoo Finance data.

### How do I read or refresh a Sentiment brief?

The English report contains a takeaway, short summary, recent events, financial or fund context, price/volume, risks and counterarguments, and one next check. It is limited to 800 words and may be shorter when evidence is limited. Research sections appear directly; expand Evidence for sources, dates, metrics and gaps. The App does not independently verify generated analysis. Yahoo news starts with headlines; optional web research adds excerpts and reads selected articles when needed. A report does not mean every article was read. Quarterly statements retain their periods and currencies; supplemental snapshots and fund holdings can still have missing dates or partial coverage.

For supported US assets, price context also compares 5, 20 and 60 completed trading sessions with market or sector references. Stocks can use SPY and a recognized sector ETF; supported equity fund categories use SPY, and supported bond categories use AGG. These are broad research proxies and may differ from the asset's exposure or a fund's official benchmark. Global, commodity, leveraged and unclassified funds may have no automatic reference. Comparisons use matching dates and currencies, state whether returns use adjusted closes or price-only closes, and show differences in percentage points. Missing comparisons remain gaps rather than zero returns.

Completed PCC reports are saved on this device for one hour from generation. Switching tabs or reopening the asset reuses a fresh report. After an hour, entering Sentiment starts a new analysis. Tap Refresh to analyze again immediately. If a refresh fails or is cancelled, the displayed report keeps its original timestamp. The first time you revisit an asset after upgrading, a report previously generated on-device is replaced when PCC is available.

Search results are cached for 15 minutes, article excerpts for 7 days, company/fund context for 6 hours, and asset and benchmark daily charts for 1 hour. Source retrieval times are preserved. To refetch stored research, use Settings → Web Research → Clear Cached Research, then tap Refresh in Sentiment. Clearing removes stored research and report copies without deleting keys or an already displayed report. The cache is on this device, excluded from backup/iCloud, and may be purged by iOS.

### Why did a price alert arrive late or not arrive?

Allow notifications for Clean Stock and enable Background App Refresh. The alert must also be enabled in the App. Background checks depend on iOS scheduling, network access, and provider data; immediate delivery is not guaranteed. The App does not monitor prices continuously.

### Does Paper Trading use real money?

No. Its cash, positions, and trades are virtual. Clean Stock does not connect to a brokerage or place real orders. Simulated results do not predict actual trading results.

### Where are my records stored, and how do I delete them?

App records are saved on your device and may sync through your Apple Account when iCloud is available. Use the App's delete or reset controls where provided. With sync active, deletions may also reach your other devices. Deleting the App alone does not guarantee removal of iCloud copies or backups; manage those through your iCloud settings. See the Privacy Policy for the data handled by each service.

### Is Clean Stock financial advice?

No. Clean Stock is for informational purposes only and does not provide investment, financial, tax, legal, or other professional advice.

## Documents

- [Privacy Policy](/CleanStock/privacy_policy/)
- [Terms of Service](/CleanStock/terms_of_service/)

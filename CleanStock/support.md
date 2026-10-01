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

### Why is Sentiment missing or unavailable?

Open a stock or ETF, scroll below the chart and statistics, and select Sentiment.

Sentiment requires iOS 27 or later and an eligible Apple Intelligence device. It is hidden on iOS 26 and when both Apple's cloud and on-device models report that the device is ineligible. Availability also depends on Apple's supported regions and settings.

On an eligible device, enable Apple Intelligence in Settings and allow any required model download to finish. Temporary setup, network, or quota problems may leave the tab visible with an explanation. When a retry is offered, try again after resolving the issue.

### Where does Sentiment analysis run?

The App prefers Apple Private Cloud Compute. If it cannot use that service, an available Apple model on your device may be used with a notice explaining the fallback. Analysis uses the selected asset's news, market data, and available company or fund information, plus web excerpts when configured; it does not include your personal holding quantities, paper trades, or notes. Retrieving data still needs a connection when the model runs on your device. Summaries can be incorrect and are not investment recommendations.

### How do I enable broader web research?

On iOS 27 or later, open Settings → Web Research and save your own [Tavily API key](https://app.tavily.com/) and/or [Brave Search API key](https://api-dashboard.search.brave.com/). Tavily is preferred; Brave can provide backup search or work on its own. The overview researches events, financials, risks and industry, then can investigate specific gaps. Search excerpts are used first; reading Yahoo or publisher articles when needed requires Tavily. The App connects directly to the providers, with no server setup. Saving a key does not test it or make a request.

Each analysis permits up to six actual search requests and two article reads, shared across provider/model fallback and retries. Cache hits do not spend a request. Your provider plans, limits and charges apply; this is not a fixed price per analysis. A missing or rejected key, rate limit or unreadable page preserves the available evidence and adds an explanation. Search excerpts are not full articles, and search dates may be estimated publication or update dates. Coverage varies by asset and publisher.

Each key stays in this device's Keychain and is not sent to the model. Remove Key disables that provider for future analyses. To change a key, remove it before adding another. Without any search key, Sentiment uses the available Yahoo Finance data.

### How do I read or refresh a Sentiment brief?

The English report contains a takeaway, short summary, recent events, financial or fund context, price/volume, risks and counterarguments, and one next check. It is limited to 800 words and may be shorter when evidence is limited. Research sections appear directly; expand Evidence for sources, dates, metrics and gaps. The App does not independently verify generated analysis. Yahoo news starts with headlines; optional web research adds excerpts and reads selected articles when needed. A report does not mean every article was read. Quarterly statements retain their periods and currencies; supplemental snapshots and fund holdings can still have missing dates or partial coverage.

For supported US assets, price context also compares 5, 20 and 60 completed trading sessions with market or sector references. Stocks can use SPY and a recognized sector ETF; supported equity fund categories use SPY, and supported bond categories use AGG. These are broad research proxies and may differ from the asset's exposure or a fund's official benchmark. Global, commodity, leveraged and unclassified funds may have no automatic reference. Comparisons use matching dates and currencies, state whether returns use adjusted closes or price-only closes, and show differences in percentage points. Missing comparisons remain gaps rather than zero returns.

Completed reports are saved on this device and reused for 1 hour from their generation time. Switching tabs or reopening the same asset uses the saved report while it remains fresh. After an hour, entering Sentiment starts a new analysis. Tap Refresh to analyze again immediately with refreshed quotes and available research. If a refresh fails or is cancelled, the displayed report keeps its original update time.

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

---
title: Clean Stock Privacy Policy
permalink: /CleanStock/privacy_policy/
---

# Privacy Policy

**Last Updated:** September 30, 2026

Clean Stock ("we," "our," or "us") respects your privacy. This Privacy Policy explains how information is handled when you use the Clean Stock mobile application (the "App").

## Information We Collect

Clean Stock does not require an account and does not ask for your name, email address, phone number, payment information, contacts, photos, location, or health data.

Your watchlists, saved assets, portfolio allocations and holdings, price alerts, and paper trading records, including optional trade notes, are stored on your device. When iCloud is available for the App, these records may also sync through Apple's CloudKit service under your Apple Account. Preferences are stored on your device. We do not operate a separate Clean Stock account system or a developer-hosted database for these records.

## Market, Fund, and News Data

When you search for tickers, refresh prices, view charts, load fund data, compare benchmarks, or open news, the App sends the relevant search terms, ticker symbols, time ranges, and request details to the providers needed to return that information. These services include Yahoo Finance, Alpha Vantage when configured for fund holdings, and FRED for inflation data. Requests for market information do not include your personal holding quantities, virtual trades, or trade notes.

Providers may receive your IP address, request headers, service cookies, and other network metadata. Opening a linked news article also connects you to the publisher's website. Each provider or publisher handles information under its own terms and privacy policy; this policy does not promise that those services immediately delete request logs.

## AI and Sentiment Features

On eligible devices running iOS 27 or later, Sentiment uses Apple's Foundation Models to produce a structured research report. The model retrieves recent headlines, market data, and available company or fund information. The App prefers Apple Private Cloud Compute (PCC), which processes the request on Apple's servers.

A PCC request can include the selected asset's symbol and name, analysis instructions, headlines, prices and volume, calculated price indicators, market and sector benchmark comparisons, valuation metrics, reported earnings, estimates and calendar dates, quarterly financial statements and snapshots, or fund descriptions, fees, holdings and sector weights. Available chart context and retrieved web excerpts may also be included. The App does not add your full watchlist, personal holding quantities, paper trades, or trade notes to the analysis request. Apple provides the processing service under its applicable privacy terms.

If PCC is unavailable or encounters a recoverable quota, connection, or service issue, the App may use an available Apple model on your device and explain the reason. In that case, model inference takes place on the device, while retrieving news and market data still uses network services. Sentiment is hidden on iOS 26 and when both Apple models report that the device is ineligible; temporary setup or service issues may instead show guidance.

### Optional web research

You can add your own Tavily and/or Brave Search API keys in Settings → Web Research. When you request Sentiment analysis, the App sends the selected asset's name and ticker and research queries directly to the configured providers. Tavily is preferred; Brave can provide backup search or work on its own. Selected article URLs go to Tavily when more detail is needed. Each provider receives only its own key to authorize requests. Retrieved excerpts may be included in the Apple model's context. See [Tavily's privacy policy](https://www.tavily.com/privacy) and [Brave's API privacy information](https://api-dashboard.search.brave.com/documentation/resources/privacy-notice).

Keys are stored in this device's Keychain with device-only protection; the App does not sync them through iCloud or include them in model prompts or app logs. Saving a key does not send a search request. Remove Key deletes that credential for future analyses; it does not revoke it or delete prior requests at the provider. We do not operate a Clean Stock backend for this feature.

Retrieved research and completed Sentiment reports are cached in the App's local Caches storage, excluded from backup and iCloud. Reports can be reused for 1 hour from generation, search results for 15 minutes, article excerpts for 7 days, company/fund context for 6 hours, and asset and benchmark daily charts for 1 hour. Original generation and retrieval times are retained. This disposable cache is size-limited; expired entries are removed when accessed and iOS may purge files. Clear Cached Research in Web Research removes stored research and report copies without deleting saved keys or an already displayed report.

## Analytics and Advertising

Clean Stock does not include third-party advertising.

Clean Stock does not use third-party analytics to track you across apps or websites.

## How We Use Information

Information handled by the App is used to:

- Save and display your app records, and sync them through iCloud when available.
- Search for market symbols.
- Retrieve quotes, charts, benchmark comparisons, ETF holdings, fund details, and news.
- Produce Sentiment summaries when you use that feature.
- Respond to support requests if you contact us.

## Sharing of Information

We do not sell personal information.

App records may be handled by Apple for iCloud sync. Selected asset context may be handled by Apple for PCC analysis, and request details are sent to market and news services as described above. If you email support, we receive your email address, message, and any attachments you choose to send. Please avoid including brokerage credentials or other information that is not needed to explain the issue.

We may disclose information if required by law or to protect our rights, users, or the security of the App.

## Data Storage and Retention

You can use the App's delete and reset controls, where available, to remove records. When iCloud sync is active, record deletions may also sync to your other devices. Removing the App can remove its local data, but does not by itself guarantee removal of iCloud copies or device backups. Manage those copies through your Apple Account and iCloud settings.

Apple and other providers govern retention of information handled by their services under their own policies. Support correspondence is held in our support email account; you can contact us to request removal of information you sent to support. We do not have access to your private iCloud records through a Clean Stock login or support account.

## Children's Privacy

Clean Stock is not directed to children under 13. We do not knowingly collect personal information from children under 13.

## Financial Disclaimer

Clean Stock provides market information for general informational purposes only. It does not provide investment, financial, tax, legal, or other professional advice. Market data may be delayed, incomplete, or inaccurate.

## Changes to This Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last Updated" date.

## Contact Us

If you have questions about this Privacy Policy, contact us at [civetworks@outlook.com](mailto:civetworks@outlook.com).

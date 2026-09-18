# Privacy Policy for Trimal

**Last updated:** September 17, 2026

This Privacy Policy describes how your personal information is handled in Trimal.

## Collection and Use of Information

**Trimal does not operate an account system, analytics service, or advertising service. We do not receive your saved cities, currency preferences, journal entries, or entered amounts on our own servers.**

Your saved cities, app preferences, home city, current destination, home currency, per-city contact hours, ordered currency list, active input currency, and last valid source currency and amount are stored on your device. Downloaded reference rates and the last snapshot base are also stored locally so they can be used offline, including after that base currency is removed from the visible list. Currency calculations and basic arithmetic expressions are evaluated on your device; entered amounts and expressions are never included in exchange-rate requests. The last valid numeric value is saved, rather than an expression history.

Trip currency suggestions are computed on your device from saved cities' region names and time zones. The app does not send your city list to a service to generate these suggestions. Currency selection history is no longer kept; previously stored recent choices are removed when the app initializes currency preferences.

Destination currency defaults and shared contact-hour windows are also computed locally from saved preferences and time zones. Contact hours and home/destination city identifiers are not sent to external services. These features do not require access to your contacts or calendar.

## Travel Journal, Camera, Photos, and Location

Journal entries are stored locally in a separate file. An entry includes its amount, currency, category, notes, city/country/time-zone snapshot, dates, and any saved reference exchange quote. Journal’s base currency is stored in local preferences; changing it calculates displayed conversions and group totals on the device. Entries are not sent to our servers. Reference-rate requests include a currency code, without the entry amount, notes, dates of spending, or location. There is no account or cross-device journal sync.

The journal place picker keeps up to five recently used city snapshots in local preferences, updated when you successfully save a new entry or change an entry's place. These include city, country, and time zone, without coordinates. City searches use Apple Maps, as in the Time tab; the app does not keep a search-query history. Recent cities remain available after restarting and do not add cities to World Time.

Receipt image recognition requires iOS 27 and available Apple Intelligence. Camera and Photos are hidden on iOS 26, on devices that do not support Apple Intelligence or have it turned off, and when no receipt model is ready; manual entry remains available. Camera access is requested only when you choose Camera. Photos uses Apple’s system picker for the image you select, without requesting access to your entire library. Receipt images are resized and their original location metadata is removed. Trimal first uses Apple’s Private Cloud Compute (PCC), which receives the selected receipt image, extraction instructions and any city-tool results needed to return amount, currency, category, date/time, city and a short note. PCC requires a connection and available service quota. If PCC is unavailable or its request fails, Trimal can use the on-device Foundation Models image model when available. If recognition remains unavailable, fails or times out, enter the details manually. The app does not use Vision/OCR or a non-Apple image recognition service. Trimal does not store the image or model session or send them to our own servers. Images are not attached to entries; choosing an image does not alter the original in Photos. An image stored only in iCloud may need to be downloaded by the system picker.

The model can call a constrained city lookup tool: known cities resolve locally, and only city/country queries go to Apple Maps when needed, not the merchant, street address, amount, notes or full receipt. City, country, time zone and local currency from this tool can be returned to the selected Apple model, including PCC. Queries are limited and cached during the recognition flow. Debug builds can display temporary recognition fields, stages and errors in the editor; this diagnostic content is not saved with entries or written to logs.

Location is optional. Choosing Use Current Location requests permission the first time. After permission is granted, new entries automatically request a single location reading to fill in the current city; manual location choices and existing entries are not overwritten. Without permission, opening a new entry does not request access. Apple Maps receives the location to determine the city, country, and time zone. Trimal saves those place names and the time zone after you save the entry, not the coordinates or a continuous location history. The app does not request background location access. City search and recent cities remain available without location permission.

## City and Country Background Photos

Journal place banners request photographs from Wikimedia services (Wikidata, Wikipedia, and Wikimedia Commons). Photo lookup sends only the city and country names represented by a banner. It does not send amounts, notes, spending dates, receipt images, device coordinates, or an account identifier. Wikimedia receives the network information needed to serve these requests, such as your IP address. The app does not request photo-library or location permission for banner photos.

Photo metadata, including public place names and attribution, and downloaded thumbnails are cached separately on your device. The cache has size limits and may be removed by the app or operating system; deleting an expense does not immediately clear its cached public background photo. A missing image or failed request leaves the plain banner visible. This photo cache is separate from receipt recognition; receipt images remain temporary and are never stored with entries.

## Data Retention

Trimal does not retain your app data on our servers. You can remove saved cities within the app, clear home/destination selections, or disable a city's contact hours in Trip & Contact Hours. Removing a saved city clears its trip associations and contact window, while retaining your home currency preference. You can edit or delete journal entries from their menus. Deleting a saved city does not delete journal entries, which retain their own place snapshots. Deleting the app removes its locally stored entries, settings, exchange-rate cache, and city-photo cache. Device backups are managed through your operating-system settings.

## Third-Party Services

Trimal uses external services to provide specific features:

- Apple's Private Cloud Compute receives selected receipt images, extraction prompts and city-tool outputs when used for receipt recognition. See [Apple’s PCC overview](https://developer.apple.com/private-cloud-compute/).
- Apple's MapKit receives searches for cities and places, including extracted receipt city/country queries, and, when you use location, including automatic city defaults for new entries after authorization, the location used to look up your current city. WeatherKit receives the coordinates of saved places when requesting weather.
- Wikimedia services receive city/country photo queries and requests for the associated photo metadata and thumbnails. No journal contents or device coordinates are included.
- Frankfurter receives requests for its currency catalog and reference exchange rates. Rate requests include the selected base currency code, but not the amount you enter, your saved city list, or an account identifier. Network requests also expose information needed to deliver the response, such as a network address, to the service infrastructure.

These services process requests under their own policies. See [Apple's privacy policy](https://www.apple.com/legal/privacy/), the [Wikimedia privacy policy](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy), and the [Frankfurter API privacy information](https://frankfurter.dev/#faq). Trimal does not use advertising or analytics SDKs.

## Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. We will notify you of any changes by posting the new Privacy Policy on this page.

## Contact Us

If you have any questions about this Privacy Policy, please contact us at civetworks@outlook.com.

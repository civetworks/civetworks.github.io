---
title: MetroMinute Privacy Policy
permalink: /MetroMinute/privacy_policy/
---

# Privacy Policy for MetroMinute

**Last updated:** October 23, 2026

This policy explains how MetroMinute and its Nearby Departures Home Screen widgets handle information. The app does not have an account system, advertising, analytics SDK, tracking SDK, or developer-operated backend.

## Location

Location access is optional in the app. When you allow it, MetroMinute requests a current location while the app is in use to select a supported metro area and find a nearby transit stop. You can instead choose an area and stop manually.

If you also allow location access for widgets, a Nearby Departures widget can request an in-use location when iOS runs its update. iOS controls when that access and update are available. The app and widgets do not continuously track location, request Always location access, or maintain a location history.

Coordinates are processed on your device. MetroMinute does not save them in its preferences or widget cache, send them to the developer, or include them in transit-data requests. You can change location permission in iOS Settings.

## Local Preferences and Widget Data

MetroMinute stores your area selection, included transit systems, chosen stops, up to four recent stops per area, and selected system tabs on your device. The app shares relevant preferences with its widget through a local shared container.

The widget also stores its latest departure board, including stop and system identifiers, route and destination information, and arrival times. This can be displayed as **Last nearby** when location is temporarily unavailable and permission is still granted. Expired departures are not eligible for that fallback. The cache contains stop information, not coordinates or a history of locations.

Local diagnostic messages record permission states and technical error codes to help investigate location failures. These messages do not include coordinates or stop names, and MetroMinute does not automatically send them to the developer.

## Transit Services and Network Requests

The app and widget request transit information directly from third-party services. Depending on the selected area and included systems, these include:

- Metropolitan Transportation Authority (MTA)
- Port Authority of New York and New Jersey (PATH)
- NYC Ferry, through its Connexionz-hosted data service
- Bay Area Rapid Transit (BART)
- 511 Open Data for Caltrain
- Massachusetts Bay Transportation Authority (MBTA)
- Chicago Transit Authority (CTA)

Requests use transit identifiers, such as a system, feed, or stop identifier, rather than your location coordinates. The service operators and network providers may receive standard connection information, including your IP address. Their handling and retention of that information are subject to their own policies. MetroMinute does not operate those services or receive their server logs.

If you open an official link from a service alert, the destination website handles that visit under its own policies.

## Station Photos and Photo Services

When a stop header requests a station photo, the app sends the catalog's reviewed station article title to Wikipedia. It then requests the image URL returned by that service, typically from Wikimedia image hosting. These requests do not include your GPS coordinates, but the stop name can identify an area you selected or a nearby stop chosen using location. Photo requests can occur for manually selected stops even when location permission is off. The widget does not request station photos.

The service operators receive the requested names or URLs and standard connection information, including your IP address. Wikimedia's handling of that information is described in its [Privacy Policy](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy); other image hosts may apply their own policies. MetroMinute does not operate those services or receive their server logs.

Photo results are cached in memory by transit system, stop identifier and reviewed title, with limits of 64 entries and 16 MiB of image data. Successful images can be reused for up to seven days and missing-image results for 30 minutes. Failed or cancelled requests are not saved as missing photos. A dedicated on-device HTTP cache has a 16 MiB memory and 100 MiB disk budget and follows the services' freshness headers. These budgets and reuse intervals are not guaranteed disk-deletion deadlines or promises of offline availability. The old stop-name-to-photo-URL preference mapping is removed when the photo service initializes.

## Public News and On-Device Classification

While the app is active in New York City with MTA included, it can request public news feeds to identify reports of subway shootings that occurred that New York calendar day. Sources include ABC7, NBC New York, Gothamist, PIX11, amNewYork, New York Post, CBS, Google News, GDELT, and Notify NYC/Everbridge. Search requests use fixed citywide terms; they do not include your coordinates, selected stop, station identifier or personal search history. Requests are no more frequent than hourly per source, and service limits or errors can delay them further. The widget does not fetch news.

These services receive the requested URLs or search terms and ordinary connection information such as IP addresses. Their own policies govern their handling and retention. Opening a report link sends a normal website request to the publisher or linked service. MetroMinute does not receive their server logs.

On compatible devices with Apple Intelligence available, candidate article text is classified locally using Apple's on-device Foundation Models framework. MetroMinute does not send article text, coordinates or station identifiers to a remote AI service. There is no cloud-classification fallback.

The app saves feed articles, response validators, refresh and retry deadlines, recent classification fingerprints, and accepted reports in its local Application Support directory. Local diagnostic logs record technical failures, model availability, timing, resource state and counts; model-performance logs do not include article text, URLs or location and are not automatically sent to the developer.

## Support Correspondence

If you email support, the developer receives your email address and the content you choose to send, including any attachments. Email is handled through the support email service and is used to respond to your request and related follow-up. Please avoid sending precise location histories, unrelated personal information, or full device logs. You can contact the same address to request deletion of your support correspondence.

## Retention and Deletion

Location fixes are used for the current operation and are not saved as a location history. Preferences remain locally until changed or the app's data is removed. Photo results in memory are bounded and expire as described above; cached network responses may be evicted or removed by the system. New widget boards replace the previous cached board; a stored board may remain on disk after its departures expire, but those departures cannot be reused as fallback content.

News notices stop displaying at the following midnight in New York. Expired reports and classification fingerprints older than 48 hours are pruned during cache maintenance; feed contents are replaced by later successful responses. If the app is inactive, saved news data can remain on disk beyond those display or reuse intervals. No location history is stored with the news cache.

To remove local app and widget data, delete MetroMinute through iOS Settings. Offloading the app or removing only a widget does not erase all saved app data. Any device backups are managed through your backup settings. MetroMinute does not provide an account or developer cloud copy that needs a separate account-deletion request.

Support correspondence is retained for handling the request and related follow-up; contact support about deletion. Deleting the app does not delete email correspondence or records held independently by transit, photo or news-service operators.

## Advertising, Tracking, and Children

The developer does not sell or rent personal information or use it for advertising or tracking. MetroMinute does not knowingly collect personal information from children through the app and has no social, messaging, or user-generated-content features.

## Security and Policy Updates

MetroMinute uses iOS networking and security capabilities, including HTTPS for transit, photo and news requests. No method of storage or transmission is completely secure. This page will be updated when the app's practices change, with a revised date above.

## Contact

For privacy questions or support-data requests, email [civetworks@outlook.com](mailto:civetworks@outlook.com).

- [Support](/MetroMinute/support/)
- [Terms of Service](/MetroMinute/terms_of_service/)

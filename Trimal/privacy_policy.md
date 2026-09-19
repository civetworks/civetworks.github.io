# Privacy Policy for Trimal

**Last updated:** September 19, 2026

Trimal does not operate an account system, advertising service or analytics service. We do not receive your saved cities, preferences, entered amounts or expenses on our own servers. Some optional features send information to the services described below.

## Data on your device

Saved cities, home and destination settings, contact hours, currency preferences, the last valid input amount and downloaded reference rates are stored locally. Time calculations, arithmetic, currency conversion and currency suggestions run on your device. Entered amounts and expressions are not included in exchange-rate requests.

Spending entries are stored in a separate local file. They include the amount, currency, category, date, notes, city/country/time-zone snapshot and any saved reference exchange quote. The app also keeps your Spending display currency and up to five cities recently selected for entries. These saved expense locations contain no device coordinates. There is no app-managed account or cross-device expense sync.

## Receipt photos and Apple Intelligence

Receipt recognition is optional. Camera and Photos are available only on supported iOS 27 devices with Apple Intelligence enabled and an available image model. Camera permission is requested when you choose Camera. Photos uses Apple's system picker for the image you select, without access to your entire library.

Trimal resizes the image and removes its original location metadata. Content visible within the photo remains part of the image. Recognition first uses Apple's Private Cloud Compute (PCC), which receives the image, extraction instructions and necessary city-lookup results. If PCC is unavailable or fails, an available on-device model may process the image instead. PCC requires a connection and available service quota.

The recognition flow may look up a printed city. Known cities resolve locally; otherwise only a city/country query is sent to Apple Maps. Merchant names, street addresses, amounts and the full receipt are not sent in that Maps query. The resolved city, country, time zone and local currency may be returned to the selected Apple model, including PCC.

Receipt images and model sessions are temporary and are not saved by Trimal or attached to expenses. Only the fields you save become an entry. The original photo in your library is unchanged; an iCloud-only photo may first be downloaded by the system picker. Manual entry remains available without recognition.

## External services and location

| Service | Information sent for the requested feature |
| --- | --- |
| Apple PCC | Selected receipt image, extraction instructions and necessary city-lookup results, as described above. |
| Apple Maps | City search text, receipt city/country queries, or an authorized location reading to find your current city. |
| Apple WeatherKit | Coordinates of saved places when requesting their weather. |
| Frankfurter | Currency catalog and reference-rate requests, including the base currency code. No entered amount, expression, expense notes or spending dates. |
| Wikimedia services | City/country names for Spending banner photos, followed by requests for public photo metadata and thumbnails. No expenses, receipt images or device coordinates. |

Network services also receive information needed to deliver a response, such as your IP address. They process requests under their own policies: [Apple](https://www.apple.com/legal/privacy/), [Wikimedia](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy), and [Frankfurter service information](https://frankfurter.dev/#faq). Apple also provides an [overview of PCC](https://developer.apple.com/private-cloud-compute/).

Location access is optional. Choosing Use Current Location requests permission; once granted, later new entries may request a single location reading to fill the current city. Trimal does not request background location access or save a continuous location history. Spending entries save the resolved place names and time zone, not the device coordinates. You can revoke permission in iOS Settings and continue choosing cities manually.

## Storage and deletion

You can edit or delete expenses and remove saved cities in the app. Deleting a saved city does not delete expenses with their own place snapshots. Removing a city clears its associated trip selection and contact hours. Recently selected cities remain in local preferences until replaced by later choices or the app's data is deleted.

Reference rates and public banner photos are cached locally. The photo cache has size limits and can be cleared by the app or operating system; deleting an expense does not immediately remove a cached public photo. Receipt images are not part of these caches.

Deleting the app removes its local app data. Original photos in your library and device backups are managed separately through your operating-system settings. We do not hold a server copy of your expenses that we can restore.

## Contact and changes

For privacy questions, contact [civetworks@outlook.com](mailto:civetworks@outlook.com). Updates to this policy will be posted here with a revised date.

[Support](support.html) · [Terms of Service](terms_of_service.html)

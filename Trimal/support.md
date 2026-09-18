# Trimal Support

## Your Travel Companion for Time and Prices

Trimal brings world time, currency conversion, and an expense journal together for international travel. Save your home city and destinations in the Time tab to compare local times and arrange a call. Switch to Currency when you want to understand a local price in a familiar currency. Use Journal to record spending along a timeline of the places you visit.

The tabs use the same saved cities to suggest currencies for your trip. For example, adding Tokyo and London makes JPY and GBP available as trip suggestions in the currency picker; you can also choose from All currencies.

Trimal remembers the last tab you used and opens it again the next time you launch the app. Your first launch opens Time.

### Frequently Asked Questions

**How do I add a new city?**  
Open the three-dot menu in the top right corner of the Time tab and choose Add City. You can search for a city or place and add it to your list.

**How do I use the Time Slider?**  
Tap any city in your list—your local city or a destination—to expand it. Drag the timeline left or right to change the time. All other cities update instantly to show the corresponding local time and date.

**How do I set my current destination?**

Open the Time tab’s three-dot menu and choose Trip & Contact Hours. Select your home city and current destination from your saved cities. Choosing a home city suggests its currency; you can also choose your home currency separately. Home and destination receive icons in the city list.

Changing the destination or home currency puts both currencies first and selects the destination currency for input, keeping the entered number and other saved currencies. This waits until you finish entering an amount, selecting a currency, or editing the list. Later manual choices and ordering stay until the trip settings change. If the destination currency cannot be determined or is unavailable, your current list stays in place.

**How do I find a good time to call?**

In Trip & Contact Hours, open each city you want to include, enable it, choose its preferred local hours, and tap Done. An end earlier than the start means the next day; the two times must differ. Each window repeats daily in that city’s time zone, including daylight saving changes.

Expand any city’s timeline. Green areas show when all configured cities are available. Drag the timeline to compare another time or day; if no green area appears, there is no shared window in the part of the timeline shown. Cities without a configured window are not included. Deleting a city clears its home/destination association and contact hours, while your home currency stays saved.

**What do the sunrise and sunset icons show?**

They show the selected day’s sunrise and sunset in that city’s local time zone. Dragging the timeline to another day updates them when data is available. Missing events are omitted. Sun times load independently, so a failed request does not hide the temperature. The temperature keeps the existing apparent-temperature value and unit, without the “Feels” prefix; UV is no longer shown.

**How do I delete a city?**  
Open the three-dot menu and choose Edit Cities, then use the delete control on the city row. While editing, a Done button replaces the menu in the top right. Tap Done to finish editing and restore the menu.

**How do I update the temperature and sun times?**

Pull down on the city list in Time. This requests updated weather and sunrise/sunset data for your saved cities while keeping your selected timeline time. Trimal also checks for expired weather data while the live clock runs and when you return to the app. If an update fails, available data for the same location and selected time remains visible.

**How do I record an expense?**

Open Journal and tap the purple + glass button. On iOS 26, it opens manual entry directly. On iOS 27, choose Camera to scan a receipt, Photos to read an existing image, or Enter manually. The editor starts with a currency heading showing its flag, name, and code, with the amount beneath it, just like the Currency tab. Category follows, then time and a right-aligned city on one row, and a white Notes card at the bottom. A positive amount is required; the other fields have defaults. The current destination provides initial city and currency choices; Journal’s base currency is used for the reference conversion.

Camera and Photos on iOS 27 first use Apple’s Private Cloud Compute, which requires a connection and available quota. If PCC is unavailable or its request fails, Trimal tries the on-device Foundation Models image model when available. Each model has its own 33-second timeout; a fallback can therefore take longer than 33 seconds in total. With Apple Intelligence enabled and available, Trimal prefills amount, currency, category, date/time, city and a short note. The model can look up the printed city to confirm its time zone and local currency. The receipt’s explicit currency takes priority; otherwise, Trimal can infer the default currency from its country. Your chosen currency is preserved. Review every field before saving; missing or uncertain details keep the defaults, and your manual edits are preserved. AI date and time fields prefill the entry after calendar validation. A printed UTC offset or identified city’s time zone takes priority; otherwise, the editor uses your phone’s current time zone. Check this time before saving. Manually chosen times are preserved. Known cities resolve locally; other city/country names are looked up with Apple Maps. If Apple Intelligence is unavailable or recognition fails, enter the details manually. A recognized amount with an uncertain currency can be reviewed and selected after you choose the receipt’s currency. Receipt images are not displayed or attached to the saved entry. Tap Save to add the entry, tap an entry to edit it, or use its menu to delete it after confirmation.

**Do I need to create a trip?**

No. Entries form one timeline with the newest first. Consecutive entries in the same city share a banner that stays at the top while you scroll, until the next banner replaces it. Once the last entry scrolls behind the banner, its bottom corners round off; scrolling back reconnects it to the entries. Use the Journal menu to switch between city and country grouping. A return visit remains a separate section when another city or country falls between visits. Accessibility text sizes let banners scroll away to leave room for entries.

**Where do the place banner photos come from?**

Banners download real city or country photos from Wikimedia Commons. The app matches the place and country, then rotates through available photos for return visits. Photos are cached on this device; scrolling does not randomly change them. The top of the photo retains its colors, with a soft fade into the text area and the entry card below. The fade adapts to dark mode and increased contrast. Entry count and totals sit at the lower right, with the total aligned to the date range on the left. Banners have no separate photo-credit button or sheet; Information contains only the currency explanation and source. Some places have fewer usable photos or none, and cached images may be cleared by the system. When a photo is unavailable, the banner keeps its plain background and the journal works normally.

Photo lookup needs a connection and sends only the city and country names, without expense details or device coordinates. It does not require access to your photo library or location. Previously cached photos can appear offline.

**How do I choose the city and time?**

Tap either side of the time-and-city row. Time opens a date and time picker using your device's current time zone. City offers the same city search as Time. Without a search, it shows up to five recently used cities; typing replaces these with search results, and clearing restores them. Selecting a result fills in the place details. Recent cities are kept on this device and updated after a new entry or changed place is saved successfully, with the most recently used first. Backdating an expense does not change usage order.

Use Current Location requests permission the first time. After you allow access, new entries automatically take a single location reading and look up the city through Apple Maps. Existing entries and cities you choose yourself are not overwritten, and entered amounts or manually chosen currencies are preserved. Selecting a journal city does not add it to World Time or save coordinates in the entry. Search and current-city lookup require a connection; recent cities work offline. If permission is denied or lookup fails, you can use search or choose a recent city. Removing a city from World Time does not remove existing entries.

**What happens to old entries when I change time zones?**

All expense dates and times follow your device's current time zone, including past entries, city banner dates, and the editor. A time zone change can move a displayed expense to a different calendar day. Its saved occurrence time stays the same, so the newest-first order is preserved. Journal refreshes when the system time zone changes and when you return to the app.

**How are journal conversions calculated?**

Open Journal’s three-dot menu and choose Currency, immediately above Information, to select the currency used for all displayed conversions and group totals, including past entries and editor previews. You can search by currency name, code, or country. Journal starts with your home currency and then remembers its own choice, without changing your trip settings or the Currency tab.

Entries retain the original amount and currency, plus any saved reference quote and its date. A matching saved reference is preserved; conversion to another base uses available reference rates, with cached rates available offline. Pull down in Journal to update these display rates. Changing the base, refreshing rates, or editing only notes does not overwrite an entry’s original amount or saved quote. Editing the amount or original currency uses an available new quote. Reference amounts are estimates and may use a quote from a different day than the expense.

You can save without a rate and later choose Add reference conversion from the entry menu. If any entries lack a conversion, their group shows the selected currency with a dash and the pending count until a complete total is available. Missing conversions are never counted as zero.

Journal accepts amounts greater than zero, with up to 12 whole-number digits and 6 decimal places. Original amounts keep the precision you entered; reference conversions use the reference currency's usual display precision. Entries stay on this device, with no account or cross-device sync.

**Does Trimal work offline?**  
Saved cities and time calculations work offline. Currency conversion also works with previously downloaded rates that cover the currencies you need. Each converted row labels saved rates and shows their reference date or dates. A missing rate affects only that row. Viewing and manually editing the journal work offline on iOS 26 and later. Receipt image recognition works offline on iOS 27 with an eligible device, Apple Intelligence enabled and its model available; otherwise, enter details manually. Downloading an image that is only in iCloud, looking up the current city or resolving a new receipt city, loading rates or city background photos for the first time, searching for new places, and refreshing weather require a connection.

**How do I convert a price?**

Open the Currency tab. Use the three-dot menu and Add Currency to save more currencies, or tap a row’s currency heading to replace it. In Edit Currencies, drag the handle on the right of a row to reorder it, or use the delete control to remove it. Tap Done to finish. The list keeps at least one currency and does not allow duplicates. Search by currency name, code, or country, including aliases such as USA, UK, and RMB. English and Chinese searches work in any interface language; searching Germany or France finds EUR.

While searching, tap the floating Done button at the right above the keyboard, or the keyboard's Search key, to dismiss it and keep your search results. Cancel in the upper-left corner closes the currency picker.

The picker suggests trip currencies based on cities saved in World Time. For example, Tokyo and London suggest JPY and GBP. Suggestions follow your city order and update when the city list changes. The All currencies section is below, and searching shows matching currencies from that list. If a city's currency cannot be determined or is unavailable, it is omitted from suggestions. The picker does not keep a recent-choice history.

Tap any amount to enter a value in that currency. Every other row updates as you type, with currencies staying in place. The input row has a light tint and pencil marker. Tap the floating Done button at the right above the keyboard to resolve a valid expression and dismiss the keyboard. Tap the clear button beside the active amount to start again, or a result’s copy icon to copy its displayed number. A brief “Copied” message confirms the action. Trimal remembers your currency list, its order, the input currency, and the precise source amount. Existing currency pairs migrate automatically.

Switching between rows preserves the original calculation precision until you actually edit the amount. A result beyond the input limit remains visible and copyable; enter a smaller source amount before editing it. Switching to a currency without a usable result starts an empty input. Currencies already in the list are excluded from the picker, except the row you are replacing.

**Are these the rates my bank will charge?**

The converter uses daily reference rates from [Frankfurter](https://frankfurter.dev/), which may differ from your bank, card, or exchange service. Fees are not included. Each converted row shows the date of the reference quote used, rather than the download time. When a conversion uses two quotes through a shared base and their dates differ, both dates appear.

Open the three-dot menu in any tab and choose Information to read the reference-rate explanation and access the data-source link.

**How do I update rates?**

Pull down in the Currency tab to refresh rates. Trimal also checks for an update when you open the converter or return to the app if the saved snapshot is more than 24 hours old. A failed refresh keeps available saved rates. If no rate is available, check your connection or select another currency and try again.

**Which amounts can I enter?**

Use your app's decimal separator. You can paste amounts with properly grouped thousands separators. Amounts must be nonnegative, with up to 12 whole-number digits and 6 decimal places. Results follow the output currency's usual decimal precision, such as no decimal places for Japanese yen.

**Can I calculate before converting?**

Yes. Use +, −, × and ÷ above the amount keyboard in any currency row, or paste an expression such as `19.9×2+8`. Multiplication and division take precedence; pasted parentheses are supported. A complete expression converts immediately. Tap = or the separate Done button to replace a valid expression with its value; Done also dismisses the keyboard.

Expressions are limited to 256 characters, with final values rounded to at most six decimal places. Unfinished expressions wait for more input. Division by zero, negative final values, and results beyond the amount limit show no converted value and do not overwrite your last saved valid amount. Use the clear button to start again. The calculator provides basic arithmetic, without discount, tip, tax, or bill-splitting forms.

**Is my data private?**  
Your saved cities, home and destination settings, contact hours, currency preferences, and journal entries stay on your device. Receipt recognition first sends the selected image, extraction instructions and city-tool results to Apple Private Cloud Compute when available, with an on-device fallback. Images and model sessions are not saved with entries or sent to our own servers. Resolving a new receipt city sends only the extracted city/country query to Apple Maps. When you use location, including automatic city defaults for new entries after granting permission, Apple receives the location needed to find the city; only the city, country, and time zone are saved in the entry. Contact-hour overlaps, expressions, trip currency suggestions, and conversion amounts are calculated locally; the saved city list and entered amounts are never sent to the exchange-rate service. Requests for rates include the base currency code. Place-banner photo lookup sends only city/country names to Wikimedia; its public photos and attribution are cached separately. See the [privacy policy](./privacy_policy.md) for information about external services.

---

### Contact Us

Need help with Trimal? Found a bug or have a feature request? We're here to help!

[Email Support](mailto:civetworks@outlook.com)

---
&copy; 2026 Civet Works. All rights reserved.

[Privacy Policy](./privacy_policy.md)

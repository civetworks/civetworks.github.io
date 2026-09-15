# Trimal Support

## Your Travel Companion for Time and Prices

Trimal brings world time and currency conversion together for international travel. Save your home city and destinations in the Time tab to compare local times and arrange a call. Switch to Currency when you want to understand a local price in a familiar currency.

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

**Does Trimal work offline?**  
Saved cities and time calculations work offline. Currency conversion also works with previously downloaded rates that cover the currencies you need. Each converted row labels saved rates and shows their reference date or dates. A missing rate affects only that row. Loading rates for the first time, adding new places, and refreshing weather require a connection.

**How do I convert a price?**

Open the Currency tab. Use the three-dot menu and Add Currency to save more currencies, or tap a row’s currency heading to replace it. In Edit Currencies, drag the handle on the right of a row to reorder it, or use the delete control to remove it. Tap Done to finish. The list keeps at least one currency and does not allow duplicates. Search by currency name, code, or country, including aliases such as USA, UK, and RMB. English and Chinese searches work in any interface language; searching Germany or France finds EUR.

While searching, tap the floating Done button at the right above the keyboard, or the keyboard's Search key, to dismiss it and keep your search results. Cancel in the upper-left corner closes the currency picker.

The picker suggests trip currencies based on cities saved in World Time. For example, Tokyo and London suggest JPY and GBP. Suggestions follow your city order and update when the city list changes. The All currencies section is below, and searching shows matching currencies from that list. If a city's currency cannot be determined or is unavailable, it is omitted from suggestions. The picker does not keep a recent-choice history.

Tap any amount to enter a value in that currency. Every other row updates as you type, with currencies staying in place. The input row has a light tint and pencil marker. Tap the floating Done button at the right above the keyboard to resolve a valid expression and dismiss the keyboard. Tap the clear button beside the active amount to start again, or a result’s copy icon to copy its displayed number. A brief “Copied” message confirms the action. Trimal remembers your currency list, its order, the input currency, and the precise source amount. Existing currency pairs migrate automatically.

Switching between rows preserves the original calculation precision until you actually edit the amount. A result beyond the input limit remains visible and copyable; enter a smaller source amount before editing it. Switching to a currency without a usable result starts an empty input. Currencies already in the list are excluded from the picker, except the row you are replacing.

**Are these the rates my bank will charge?**

The converter uses daily reference rates from [Frankfurter](https://frankfurter.dev/), which may differ from your bank, card, or exchange service. Fees are not included. Each converted row shows the date of the reference quote used, rather than the download time. When a conversion uses two quotes through a shared base and their dates differ, both dates appear.

Open the three-dot menu in either Time or Currency and choose Information to read the reference-rate explanation and access the data-source link.

**How do I update rates?**

Pull down in the Currency tab to refresh rates. Trimal also checks for an update when you open the converter or return to the app if the saved snapshot is more than 24 hours old. A failed refresh keeps available saved rates. If no rate is available, check your connection or select another currency and try again.

**Which amounts can I enter?**

Use your app's decimal separator. You can paste amounts with properly grouped thousands separators. Amounts must be nonnegative, with up to 12 whole-number digits and 6 decimal places. Results follow the output currency's usual decimal precision, such as no decimal places for Japanese yen.

**Can I calculate before converting?**

Yes. Use +, −, × and ÷ above the amount keyboard in any currency row, or paste an expression such as `19.9×2+8`. Multiplication and division take precedence; pasted parentheses are supported. A complete expression converts immediately. Tap = or the separate Done button to replace a valid expression with its value; Done also dismisses the keyboard.

Expressions are limited to 256 characters, with final values rounded to at most six decimal places. Unfinished expressions wait for more input. Division by zero, negative final values, and results beyond the amount limit show no converted value and do not overwrite your last saved valid amount. Use the clear button to start again. The calculator provides basic arithmetic, without discount, tip, tax, or bill-splitting forms.

**Is my data private?**  
Your saved cities, home and destination settings, contact hours, currency preferences, and entered amounts stay on your device. Contact-hour overlaps, expressions, trip currency suggestions, and conversion amounts are calculated locally; the saved city list and entered amounts are never sent to the exchange-rate service. Requests for rates include the base currency code. See the [privacy policy](./privacy_policy.md) for information about external services.

---

### Contact Us

Need help with Trimal? Found a bug or have a feature request? We're here to help!

[Email Support](mailto:civetworks@outlook.com)

---
&copy; 2026 Civet Works. All rights reserved.

[Privacy Policy](./privacy_policy.md)

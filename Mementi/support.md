# Mementi Support

Contact [civetworks@outlook.com](mailto:civetworks@outlook.com) for help, bugs or feedback. Include the app version and the error shown. Please do not send passwords, API keys or private photos.

## How do I connect OpenRouter?

Open **Settings → OpenRouter**. Use **Sign in with OpenRouter** to authorize in the system browser, or **Enter API key** to paste an existing OpenRouter API key and choose **Verify and connect**. These are alternative methods; only one is needed. Either method stores the key in this device's Keychain. Leaving the input page cancels validation. Connect separately on each device.

If you choose **New Diary** or **New Post** before connecting, Mementi prompts you to connect first. After a successful connection, it continues the creation flow you selected. Cancelling leaves you on the current page.

## Who pays for generation?

Model requests use your OpenRouter account. OpenRouter handles usage, billing and any provider BYOK configuration. Mementi does not sell credits or subscriptions. Each initial generation, refinement or explicit retry can incur separate platform usage; the app does not automatically retry a paid request.

Usage / Limit appears in one row and belongs to the authorized API key. Unlimited means that key has no spending limit; it does not indicate an unlimited account balance. A failed lookup appears as a dash.

## How do I choose a model?

Connect OpenRouter first, then open **Settings → OpenRouter → Model**. The model picker appears only while connected. It includes models suited to writing diaries and posts from photos, with known prices. Search by model or provider, or filter by **Free** and **Paid**. Each model shows its published input/output prices in USD per million tokens. Price ranges include conditional rates; the platform determines final charges and free-model usage limits.

The automatic default is Gemini 3.8 Flash when the platform reports available credit, and a free model when credit is exhausted. If credit cannot be determined, the initial default stays free. Your explicit model choice is saved on this device, takes precedence over automatic defaults, and applies to the next generation or refinement. Browsing and selecting models does not generate content. If a selected model becomes unavailable, choose another. Prices can be refreshed by pulling down the list or using the refresh button.

## What happens to old Mementi credits?

This version no longer uses Mementi credits to permit generation or offers new credit purchases. Historical records are preserved; they are not automatically exchanged for OpenRouter funds. Contact support about a past Mementi purchase. The previous Credits / Restore Purchases screen is no longer available in this version.

## How do I disconnect or revoke access?

Use **Settings → OpenRouter → Disconnect** to remove the key from this device. To switch accounts, disconnect and then use either connection method. To revoke the platform key itself, use OpenRouter's key settings. Disconnecting locally does not cancel a request already submitted, refund usage or remove platform history.

## Why did generation fail?

- **Connection required or expired:** Connect or reconnect your OpenRouter account.
- **Platform allowance unavailable:** Review your key limit, account availability and provider settings on OpenRouter.
- **Rate limit:** Wait for the platform's limit to clear before retrying.
- **Network or timeout:** Check connectivity. A timed-out request may already have incurred usage; retry only when you want a new request.
- **Invalid output or unavailable provider:** The model may have returned incomplete or incompatible content. Your photos and previous options remain available so you can try again.

If sign-in does not return to the app, cancel and retry with a working connection. The connection uses a temporary localhost address on your device and does not require a hosted callback page. Report the app version and visible error without sharing the callback URL or code.

## Where are my photos and diaries stored?

Imported photos, diaries, posts and unfinished tasks are stored locally, with optional synchronization through your personal iCloud container. Restart the app after changing its storage preference. Existing saved content remains available without an OpenRouter connection.

Online generation sends selected photos, prompts and relevant date/location metadata to OpenRouter and its model provider. Refinement also sends the selected previous text. Provider privacy and retention settings apply. See the [Privacy Policy](./privacy_policy.html) for details.

## Does Mementi access all my photos?

You select which photos to import. Mementi does not upload your entire library. Manage photo permissions in device settings.

## Does deleting the app remove everything?

Deleting the app removes its local app data, but may leave Keychain items, iCloud copies, platform data and historical purchase records. Disconnect/revoke platform access and manage iCloud storage separately as needed.

[Privacy Policy](./privacy_policy.html) · [Terms of Service](./terms_of_service.html)

© 2026 Civet Works. All rights reserved.

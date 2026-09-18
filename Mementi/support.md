# Mementi Support

Contact [civetworks@outlook.com](mailto:civetworks@outlook.com) for help, bugs or feedback. Include the app version and the error shown. Please do not send passwords, credentials or private photos.

## How do I start generating?

Use iOS 27 or later on a device and in a region that support Apple Intelligence. Enable Apple Intelligence in the system Settings and allow its model to finish downloading. Mementi checks model availability in its own **Settings → Apple Intelligence** section.

Choose **New Diary** or **New Post**, select up to 13 photos, pick a tone and generate. Mementi analyzes the photos individually, then writes three drafts. Select one to receive two refinements while retaining the original. Review the content before saving or sharing. No model account, login or API key is required.

## When does Mementi use Private Cloud Compute?

Writing starts on the device. If a request exceeds the local context budget and **Use Private Cloud Compute when needed** is enabled, Mementi tries Apple Private Cloud Compute (PCC). Only photo summaries, available date/place information and text excerpts enter this model request; original photos are analyzed on the device.

PCC is enabled by default. Turn it off in Mementi Settings to keep all model generation on the device. PCC requires internet and has an Apple-managed daily usage limit. Settings displays its availability and quota status. When Apple offers more usage options, the app can open Apple's system interface for them. Mementi does not sell credits or subscriptions.

If PCC is unavailable because of network, quota or service conditions, Mementi continues with smaller writing requests on the device. It does not repeatedly retry PCC during that generation.

## Why is generation unavailable?

- **Unsupported device or region:** Both the photo-analysis feature and PCC require an eligible Apple Intelligence device and region. See [Apple's current requirements](https://support.apple.com/en-us/121115).
- **Apple Intelligence is off:** Enable it in system Settings.
- **Model is not ready:** Wait for the system model download, then check again.
- **Unsupported language:** Choose another writing language in Mementi Settings.
- **Context limit:** The app splits writing into smaller groups. If a single group still cannot fit, reduce the input or try again later.
- **Refusal or incomplete output:** Your photos and completed stages remain available. Review the selected photos and retry if appropriate.

Existing saved diaries and posts remain readable when generation is unavailable.

## Can I cancel or resume?

Use Cancel while generating. Completed photo analysis, writing groups and candidates are saved with the unfinished task. Resume the task from history to continue. Changing photos, tone or selected reference restarts the affected writing steps while allowing valid photo summaries to be reused.

Cancelling stops further app work. It cannot undo processing or usage that Apple already completed for a submitted PCC request.

## Where are photos and diaries stored?

Photos, entries and unfinished task checkpoints use local Core Data with optional iCloud synchronization. Restart after changing the storage preference. On-device-only generation does not turn off iCloud sync or Apple's location-name lookup. See the [Privacy Policy](./privacy_policy.html).

## What happens when upgrading?

Saved photos and entries are preserved, and older unfinished task payloads remain readable. The app removes its retired local model credential and preferences. Local cleanup does not revoke old remote credentials or delete provider accounts. Historical Mementi purchase records are not automatically removed or exchanged for model usage; contact support about a past purchase.

## Does deleting the app remove everything?

Deleting the app removes its local app data but may leave iCloud copies, historical provider data and past purchase records. Manage those stores separately as needed.

[Privacy Policy](./privacy_policy.html) · [Terms of Service](./terms_of_service.html)

© 2026 Civet Works. All rights reserved.

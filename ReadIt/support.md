---
title: Read It Support
permalink: /ReadIt/support/
---

# Read It Support

For help or feedback, contact [civetworks@outlook.com](mailto:civetworks@outlook.com). Include your iPhone model, iOS version, app version and the visible error. Do not send API keys, passwords, authorization codes or private book content.

## How do I import a book?

Open Library and choose Import EPUB, or tap the + button when books are already present. Select an EPUB from Files. You can also use the iOS share sheet to send an EPUB to Read It. The app reads EPUB files; it does not supply a book catalog.

## Do I need an account?

Importing and reading books do not require an account. To create chapter audio, open Settings and choose either **Connect with OAuth** or **Enter API Key**.

OAuth opens OpenRouter in the system browser and returns after authorization. With an API key, paste a valid key into the obscured input and tap **Connect with API Key**. The app validates it before saving it securely on this iPhone. A supplied key lets you connect without registering an account or signing in through the browser.

If authorization does not return to the app, cancel and try again with a working network connection. The temporary localhost callback is handled on your own iPhone, not by this website.

## Who pays for speech?

New speech uses the OpenRouter account associated with the connected key, whether you used OAuth or entered the key directly. Model pricing, quotas and billing are managed by the service. Free models can be unavailable or rate-limited; paid models may consume credits after you select and confirm them. Read It does not sell generation credits or subscriptions. A failed or cancelled request may already have used provider resources.

## How do I change the voice or speed?

Open Settings > Voice to select and preview a voice. Use Read Aloud Model to choose an available compatible model and Speech Speed for a speed from 0.5x to 2x. Changes apply to newly requested audio; they do not change the speed of audio already playing. Different combinations keep separate caches.

Sarah, Adrian, Zixuan and Yutong are normally available. Sophie and Chloe are available to approved OpenRouter accounts. Sarah and Adrian have English previews; the other voices have Chinese previews.

## How do I download a chapter?

Open the reader's top-right menu > Contents, then tap the chapter's download icon. The title itself navigates to the chapter. Audio is generated without starting playback; the list shows received data and estimated progress when available. Use the stop button to cancel. The system task may also display Generating Audio with the chapter name.

Pausing playback or closing Contents does not cancel a download. Interrupted downloads are not resumed from a partial file; an explicit retry generates the chapter again and may cause new service usage.

## How do I remove downloads or a book?

Use the completed chapter's delete-audio button to remove that voice/model/speed version, or choose Clear Downloaded Audio in the reader menu to clear audio for the book. These actions keep the book and reading position. Remove the book from Library to delete its local reading copy and associated data.

## Why is audio unavailable or highlighting incomplete?

Check your network connection, the connected key's allowance and whether the selected model is available. Generated speech and on-device alignment can vary by voice, language and chapter. Apple speech assets may need an initial download. Keep the app open while checking a new sample and report the visible error if it persists.

## How do I disconnect or delete service data?

Settings > Disconnect removes the local key and account binding. Revoke the key or manage account history in OpenRouter separately. Deleting Read It does not necessarily remove Keychain items, device backups or provider-held data. See the Privacy Policy for details.

## Documents

- [Privacy Policy](/ReadIt/privacy_policy/)
- [Terms of Service](/ReadIt/terms_of_service/)

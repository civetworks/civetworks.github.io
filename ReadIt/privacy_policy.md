---
title: Read It Privacy Policy
permalink: /ReadIt/privacy_policy/
---

# Privacy Policy

**Last updated:** September 8, 2026

Read It is an iPhone EPUB reader provided by Civet Works. This policy explains how the public version of Read It handles information, including its optional OpenRouter-powered Read Aloud feature.

## 1. Books and reading on your device

You choose the EPUB files to import through Files or the share sheet. Read It processes the selected files and stores a local reading copy, book metadata, covers, reading positions and preferences on your iPhone. Importing or opening a book does not send its text for AI speech generation.

Read It does not operate a central book library, a Read It account system or app-managed cloud synchronization. Device backups and files you keep in services such as iCloud Drive remain subject to your Apple or file-provider settings.

## 2. Optional online speech

When you start Read Aloud for an uncached chapter or request a chapter audio download, Read It sends the chapter text to OpenRouter and the Fish Audio provider serving the selected model. Continuing playback into an uncached chapter can generate that next chapter. Requests include the selected model, voice and speech speed. Some included voices also send an app-bundled reference recording and its transcript; preset voices use a voice identifier.

These requests process text outside your device and require a network connection. The complete EPUB archive is not uploaded as a book file, but the text of each chapter you generate is sent. Submit only material you have the right to use and share with these services.

Generated audio is downloaded and cached on your device. Read It does not upload cached generated audio for highlighting: it uses Apple's on-device Speech processing to align the speech with the book text. Speech assets may need to be downloaded from Apple. The app does not record your microphone or offer a way to record, import or create your own voice profile.

Pausing playback, closing the reader or locking the phone does not necessarily cancel an active generation request. Use the generation cancellation control to stop a task. Cancellation cannot undo processing already performed by a provider.

## 3. OpenRouter connection and account information

You can connect to OpenRouter through OAuth or enter an API key directly in Settings. For OAuth, Read It opens the system browser authentication session and does not receive your OpenRouter password. A temporary listener on the device's loopback interface receives the authorization callback; it is not a callback to the Civet Works website or another device on your network.

For direct key entry, the input is obscured. The key is sent to OpenRouter to validate it and retrieve its associated account/key information before it is saved. This path does not require browser sign-in. Leaving the entry page clears the input draft and cancels an unfinished validation.

For either connection method, the app stores the API key and available OpenRouter account ID in this device's Keychain with synchronization disabled. It uses the key to request speech and retrieve account/key status, model availability, pricing and usage information. The account ID displayed in Settings is an internal service identifier; the current account integration does not obtain your email or profile username.

OpenRouter manages the platform account, authentication and billing. Information you provide on its sign-in pages is handled by OpenRouter under its policies.

## 4. Additional voice access and website requests

Some additional bundled voices are available only to approved OpenRouter accounts. Read It downloads a public configuration from our GitHub Pages website and compares an account hash on your device. The configuration request does not explicitly send your account ID, API key, device identifier or computed hash.

If you ask us to enable additional voices, we may use the account identifier you provide to administer access. The public configuration contains one-way hashes of permitted identifiers rather than the original account IDs. Hashes are pseudonymous identifiers, not a guarantee of anonymity. Removing an entry does not remove copies already held in caches or public version history.

The last valid configuration is stored locally so access can continue when the network is unavailable. Older cached rules may compare a vendor device identifier locally until a valid replacement configuration is received.

GitHub Pages hosts the configuration, support pages and these documents. GitHub logs visitor IP addresses for security when pages or files are requested. See [GitHub's Pages data collection information](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection) and [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## 5. Service providers, support and sharing

OpenRouter and Fish Audio receive speech request content and the technical information needed to deliver their services. Their retention, logging, training and international-processing practices depend on their policies, the model endpoint and your account settings. Read It does not promise zero retention or no training by every provider.

Review [OpenRouter's privacy policy](https://openrouter.ai/privacy), [OpenRouter's data collection documentation](https://openrouter.ai/docs/guides/privacy/data-collection) and [Fish Audio's privacy policy](https://fish.audio/privacy/) before submitting sensitive text. Providers may retain service metadata even when content logging is disabled.

If you contact Civet Works, we receive your email address and the information you choose to send. We use this to respond, troubleshoot problems and administer requests you make, including voice access. Do not send passwords, API keys, authorization codes, entire private books or unnecessary personal information.

Read It includes no third-party advertising or analytics SDK. Civet Works does not sell your personal information or use the app to track you across other apps and websites. We may disclose information we hold when required by law or when necessary to protect users, our rights or service security.

## 6. Retention and your controls

- Remove a book from Library to remove its local reading copy, reading records and related generated audio.
- Use a chapter's delete-audio button or Clear Downloaded Audio to remove cached speech while retaining the book. Some derived audio may also be removed by iOS cache management.
- Use Settings > Disconnect to remove the local OpenRouter key and account binding. This does not revoke the key on OpenRouter, delete its account or request history, refund usage, or undo a request already sent.
- Manage key revocation, provider settings and service-held data directly through OpenRouter and the applicable provider.
- Contact us to request access, correction or deletion of information held by Civet Works, subject to applicable requirements. We keep support correspondence only as needed to handle the request and meet legitimate recordkeeping obligations.

Deleting the app does not necessarily delete Keychain items, device backups, public configuration history or provider-held data. Manage those separately. Removing a voice-access entry takes effect on devices when they successfully refresh their configuration; cached rules can remain while offline.

## 7. Security and processing locations

Read It uses HTTPS for remote requests and the system Keychain for credentials. Its application diagnostics exclude API keys, authorization codes, chapter text and audio contents. No storage or transmission method is completely secure.

Apple, OpenRouter, Fish Audio, GitHub and our support email service may process information in different countries according to their respective practices.

## 8. Children and changes

Read It is not designed for children. Online speech is also subject to the age and eligibility requirements of OpenRouter and the model provider. Contact us if you believe a child has sent personal information to Civet Works so we can address the request.

We may update this policy to reflect changes in the app or applicable requirements. The revised policy and date will be posted here.

## 9. Contact

For privacy questions or requests, email [civetworks@outlook.com](mailto:civetworks@outlook.com).

[Support](/ReadIt/support/) · [Terms of Service](/ReadIt/terms_of_service/)

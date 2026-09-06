# Privacy Policy

**Last Updated:** September 5, 2026

Mementi, provided by Civet Works, creates diaries and social posts from photos you select. This policy describes the OpenRouter-connected version of the app.

## 1. Photos, prompts and generated content

You choose which photos to import. Mementi does not upload your entire photo library. Imported photos, diary/post content and unfinished generation tasks are stored on your device. If iCloud storage is enabled, the app can synchronize these records through your personal Apple CloudKit container.

When you request online generation or refinement, the app sends the selected, resized photos, the generation prompt, tone and language preferences, and available photo metadata such as date and location to OpenRouter and the model provider handling the request. Refinement also includes the selected previous text. This processing requires an internet connection and occurs outside your device. Opening existing saved content does not itself submit it for model generation.

## 2. OpenRouter authorization

You can sign in with OpenRouter using the system authentication session, or enter an existing OpenRouter API key in a masked input field. Mementi does not receive your platform password. OAuth exchanges a PKCE-protected authorization code for a key; manual entry verifies the key directly with OpenRouter. Both methods store the key in this device's Keychain with synchronization disabled. It is not stored in the app's content database, preferences or iCloud. The manual input is cleared when you leave its page.

During authorization the app temporarily listens on this device's loopback interface. OpenRouter redirects the system authentication session to a localhost URL containing a random session path and authorization code. The app validates that callback and closes the listener and authentication session. The callback does not go to a Civet Works website or a device on the local network. The API key and PKCE verifier are never included in the callback response.

The app uses your API key to submit generation requests and retrieve the key's reported usage and limits. When choosing an automatic default model, the app also attempts to read available account credits; if unavailable, it uses the key's reported allowance. These requests do not generate content. OpenRouter manages the platform account, model usage, billing and any provider keys you configure there. Provider retention, training and routing practices depend on their policies and your platform settings; Mementi does not control or make a blanket no-retention or no-training promise for those services.

## 3. Service providers and sharing

We do not sell your personal information. Relevant third-party services include:

- **OpenRouter and the selected model provider:** Online model requests and platform account services. Review [OpenRouter's privacy policy](https://openrouter.ai/privacy) and the applicable provider policy/settings before submitting sensitive material.
- **Apple:** Photo selection, device security and optional iCloud synchronization, subject to Apple's privacy practices.
- **GitHub Pages:** Hosting of support and policy documents, subject to GitHub's privacy practices. It does not receive authorization callbacks.

If you contact support, we receive the information you send and use it to respond. Do not send API keys, passwords or unnecessary private photos in support requests. We may disclose information when required by applicable law.

## 4. Storage and retention

Saved content and imported images remain in local storage until removed through the app or the device's storage controls. Cloud copies follow your iCloud settings and Apple's controls. Generated content is not copied to a Civet Works inference server; model requests go directly to OpenRouter.

The OpenRouter key remains in the device Keychain until you disconnect or replace it. Disconnecting removes the local key; it does not revoke the platform key or delete platform request history. Revoke access and manage retained platform data in OpenRouter separately.

This version no longer sells or consumes Mementi credits. It does not automatically erase historical credit/transaction records from earlier versions or remote purchase records. Those records may remain for handling past purchases and support; contact us for questions about them. We do not promise a six-month automatic deletion period.

## 5. Your controls

- Select only the photos you want processed, and use device settings to manage photo access.
- Use the app's storage preference and Apple's iCloud controls to manage synchronization. Restart the app after changing the storage preference.
- Delete saved entries in the app where supported, and manage local/iCloud storage through Apple settings.
- Disconnect in Mementi to remove its local OpenRouter credential. Use OpenRouter's access management to revoke the key.

Deleting the app alone does not necessarily delete device Keychain items, iCloud copies, platform data or past purchase records. Manage those stores separately. Contact us for assistance concerning data held by Civet Works.

## 6. Security and international processing

The app uses HTTPS for platform requests and the system Keychain for credentials. Generation and authentication services do not log API keys, authorization codes, verifiers, raw photos, prompts or generated responses. No transmission or storage system is guaranteed secure.

Apple, OpenRouter, model providers and the documentation hosting service may process data in different countries according to their respective practices.

## 7. Children and policy changes

Mementi is not intended for children under 13. We do not knowingly collect personal information from children under 13. Platform age and eligibility requirements also apply when using OpenRouter.

We may update this policy by publishing a revised version and date on this page.

## 8. Contact

For privacy questions, contact [civetworks@outlook.com](mailto:civetworks@outlook.com).

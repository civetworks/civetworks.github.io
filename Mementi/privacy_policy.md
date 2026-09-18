# Privacy Policy

**Last Updated:** September 17, 2026

Mementi, provided by Civet Works, creates diaries and social posts from photos you select. This policy describes the iOS 27 version using Apple Foundation Models.

## 1. Photos, text and model processing

You choose which photos to import. Mementi does not submit your entire photo library for generation. Imported photos, saved entries and unfinished tasks, including completed photo summaries and drafts, are stored on your device. If iCloud storage is enabled, these records can synchronize through your personal Apple CloudKit container.

Photo analysis uses Apple's on-device model. Writing also starts on the device. The app uses short photo summaries, your chosen tone and language, and available date and place information. Refinement uses an excerpt from your selected draft. Location-name lookup may use Apple's location services; it is separate from model generation.

When **Use Private Cloud Compute when needed** is enabled and a writing request exceeds the on-device context budget, Mementi may send photo summaries, available date/place information, writing preferences and text excerpts to Apple Private Cloud Compute (PCC). Original photos are not sent to PCC for model generation. PCC requires a network connection and is subject to Apple's usage limits and privacy practices. You can turn this setting off to keep all model generation on the device. This choice does not change your iCloud synchronization preference.

Opening saved content does not itself submit it for model generation. See [Apple's Private Cloud Compute information](https://security.apple.com/private-cloud-compute/) for details about Apple's service.

## 2. Accounts and service providers

Mementi does not require an account or a model API key and does not operate an inference proxy. Relevant services are:

- **Apple:** System model processing, optional Private Cloud Compute, photo selection, location-name lookup, device security and optional iCloud synchronization, subject to Apple's privacy practices.
- **GitHub Pages:** Hosting of support and policy documents, subject to GitHub's privacy practices. It does not receive model requests.

We do not sell your personal information. If you contact support, we receive the information you send and use it to respond. Do not include passwords, credentials or unnecessary private photos. We may disclose information when required by applicable law.

## 3. Storage and retention

Saved content and imported images remain in local storage until removed through the app or device storage controls. Cloud copies follow your iCloud settings and Apple's controls. Generated content is not copied to a Civet Works inference server. Completed generation stages are saved with unfinished tasks to support retry and recovery.

During upgrade, the app removes the retired local model credential and model preferences. This local cleanup does not revoke old platform credentials, delete data retained by previous service providers or delete remote service accounts. Manage those records with the corresponding provider if needed.

The app no longer sells or consumes Mementi credits. Historical purchase and transaction records are not automatically erased; contact support about past purchases. We do not promise a fixed automatic deletion period for those historical records.

## 4. Your controls

- Select the photos to import and manage photo access in device settings.
- Turn off Private Cloud Compute in Mementi Settings to keep model generation on the device.
- Use the app's storage setting and Apple's iCloud controls to manage synchronization. Restart the app after changing the storage preference.
- Cancel generation to stop further work. A request already submitted to Apple may already have been processed and counted toward usage.
- Delete saved entries where supported, and manage device/iCloud storage through Apple settings.

Deleting the app does not necessarily delete iCloud copies, data held by earlier service providers or past purchase records. Manage those stores separately or contact support concerning data held by Civet Works.

## 5. Security and international processing

Model requests use Apple's Foundation Models framework and system services. The generation implementation does not log raw photos, prompts, photo summaries or generated responses. No transmission or storage system is guaranteed secure.

Apple and the documentation hosting service may process data in different countries according to their respective practices. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## 6. Children and policy changes

Mementi is not intended for children under 13. We do not knowingly collect personal information from children under 13. Apple's eligibility requirements also apply to its services.

We may update this policy by publishing a revised version and date on this page.

## 7. Contact

For privacy questions, contact [civetworks@outlook.com](mailto:civetworks@outlook.com).

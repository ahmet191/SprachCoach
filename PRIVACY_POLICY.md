# SprachCoach Privacy Policy

**Effective date: September 22, 2026**

## 1. Overview

SprachCoach is a German-learning app that uses Google's Gemini service for AI-powered features such as live voice practice, teacher lessons, grammar practice, writing, dictionary lookups, photo analysis and optional conversation/exam feedback.

This policy explains what data is processed, why it is needed, where it goes and what choices you have.

SprachCoach supports two AI access modes:

- **Included AI access**, provided through Firebase AI Logic / Google Gemini.
- **Bring Your Own Key (BYOK)**, where you optionally save your own Gemini API key and use your own Gemini quota.

No email/password sign-up is required. Current versions use a pseudonymous Firebase anonymous-auth identity in the background for managed AI access and user-owned backend features.

## 2. Your AI content

When you use an AI feature, only the content needed for that feature is sent to Google's AI service. Depending on what you choose to use, this can include:

- microphone audio during a live voice session,
- live speech transcription,
- text you type,
- custom coaching instructions,
- photos you explicitly take or select for analysis,
- saved conversation transcripts when you request feedback,
- oral-exam transcripts when you request a practice assessment,
- writing or dictionary requests.

This content is used to provide the feature you requested.

### Included AI access

With included access, AI requests are sent from your device through **Firebase AI Logic** to Google's Gemini service. Firebase App Check and anonymous Firebase Authentication are used to protect the managed access flow.

SprachCoach's own server acts as a control and usage layer. It can provide AI configuration/policy and synchronize pseudonymous usage counters, but it does **not** proxy or store your AI prompts, microphone audio stream, photos, conversation transcripts or model responses.

### BYOK access

If you save your own Gemini API key, AI requests use the direct Gemini API path with your key.

Your API key:

- is stored in the iOS Keychain,
- is not sent to SprachCoach's server,
- can be replaced or deleted from Settings.

Google's processing and retention rules are governed by Google's applicable privacy policy and Gemini API terms and can depend on the service/account/tier you use.

## 3. Pseudonymous usage data sent to SprachCoach

To understand reliability, feature usage and included-AI limits, SprachCoach sends pseudonymous product/technical metadata to a developer-operated server.

This can include:

- screens, buttons and features used,
- AI request success/failure events,
- conversation duration,
- app/platform/OS version, locale and device model,
- selected CEFR level and explanation language,
- whether a custom coaching instruction is configured, **but not the instruction text**,
- included-AI usage counters and related operational metadata.

This data is linked to a random installation identifier and, in current versions, a pseudonymous Firebase anonymous-auth UID. These identifiers do not contain your name, email, Apple ID, advertising identifier or device serial number.

### What SprachCoach's server does not receive as analytics

SprachCoach's analytics/usage backend does not receive:

- microphone audio,
- photos used for AI analysis,
- AI prompts or model answers,
- conversation or exam transcripts,
- dictionary search terms,
- the text of custom coaching instructions,
- your Gemini API key.

## 4. Feedback and support

If you choose to send feedback from the app, the feedback category, title, message and support thread are stored on the developer-operated server so the developer can read and respond to them.

Feedback is linked to your pseudonymous app/Firebase identity, not to a name or email address.

Before a new feedback item is opened by support, the app may allow you to edit or delete it. Once it has been opened or answered, the conversation is retained as a support record while you can continue replying until it is closed.

Please do not include passwords, API keys or sensitive personal information in feedback messages.

## 5. Optional push notifications

Push notifications are optional.

If you explicitly enable them, SprachCoach stores an Expo push token associated with your pseudonymous app identity. Notification payloads are delivered through Expo Push Service and, on iOS, Apple Push Notification Service (APNs).

For feedback notifications, the lock-screen notification does not contain the private text of the support reply. The app retrieves the feedback thread after you open it.

You can disable SprachCoach notifications from the app settings or iOS Settings.

## 6. Data stored on your device

Depending on the features you use, SprachCoach stores data locally on your device, including:

- saved conversation transcripts and feedback reports,
- saved dictionary lookups,
- language, level and app settings,
- custom coaching instruction text,
- your privacy-consent record,
- cached AI configuration and local included-AI usage information,
- your Gemini API key if you choose BYOK.

The BYOK key is stored in the iOS Keychain. Supported local data can be deleted from within the app, and the API key can be removed from Settings.

## 7. Microphone, camera and photo-library access

SprachCoach requests system permissions only when they are needed for a feature:

- **Microphone:** used for live voice practice while a session is active.
- **Camera / Photo Library:** used when you choose to capture or select an image for AI analysis.
- **Notifications:** requested only if you choose to enable push notifications.

You can change these permissions at any time in iOS Settings.

## 8. Consent and your choices

Before core AI content or usage analytics is sent off the device, SprachCoach shows a data-sharing notice and asks for your consent.

If the required disclosure changes materially, the consent version is updated and you will be asked again.

You can withdraw consent from **Settings → Privacy & data**. Withdrawing consent stops consent-bound AI use and analytics transmission until you consent again.

Optional push notifications have their own opt-in and are not enabled unless you choose to enable them.

## 9. How data is used

Data is used only for the purposes described in this policy:

- to provide AI-powered language-learning features,
- to operate daily included-AI allowances,
- to maintain app reliability and understand feature usage,
- to provide support when you submit feedback,
- to deliver notifications you explicitly enable.

SprachCoach does not use your data for advertising, cross-app tracking or sale to data brokers, and it does not use your AI content to train a developer-owned model.

## 10. Data retention

- **On-device data** remains until you delete it using available app controls or remove the app.
- **Pseudonymous usage/operational records, included-AI counters, feedback/support threads and enabled push endpoints** may be retained for as long as reasonably needed to operate, secure, support and improve the app. There is currently no fixed automatic deletion schedule for these server-side records.
- **Google-processed AI content** is subject to Google's own retention and processing terms.

If you have a question about server-held data or a privacy request, contact the developer using the address below.

## 11. Security

SprachCoach uses encrypted network connections for data in transit. BYOK API keys are stored using the iOS Keychain. Firebase App Check and anonymous Firebase Authentication are used to protect supported managed/backend operations.

No security method can guarantee absolute protection, but the app is designed to avoid sending AI content to the SprachCoach server when that content can be processed directly by the AI provider.

## 12. Children

SprachCoach is not directed at children under 13 and does not knowingly collect identifying information from children.

## 13. Third-party services

Relevant third-party services include:

- **Google LLC / Gemini / Firebase AI Logic**
  - Google Privacy Policy: https://policies.google.com/privacy
  - Gemini API Additional Terms: https://ai.google.dev/gemini-api/terms
- **Expo Push Service** for optional push delivery
- **Apple Push Notification Service (APNs)** for optional iOS notifications

## 14. Changes to this policy

If this policy changes in a way that materially affects required data sharing or who receives that data, SprachCoach will update its disclosure and request consent again where appropriate.

## 15. Contact

Questions or privacy requests:

**ahmetcemaleddin@gmail.com**

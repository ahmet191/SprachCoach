# SprachCoach Privacy Policy

**Effective date: November 2, 2026**  
**Applies to:** SprachCoach for iOS and Android (including version 1.5) and the related SprachCoach services.

## 1. Who operates SprachCoach

SprachCoach is an independent German-learning application. For questions about this policy or requests concerning your personal data, contact the developer at **sekercideveloper@gmail.com**.

This policy explains which information is kept on your device, which information is sent to the developer-operated SprachCoach server, which information is processed by external providers, and the controls available to you.

SprachCoach provides language-learning activities, optional AI features powered by Google's Gemini service, optional user accounts, and an account-based competition feature called Arena.

## 2. Guest learning, identity and your choices

You can use local learning features without creating a verified account. When you continue as a guest, your learning history and optional profile details remain on that device; they are not automatically transferred to a server account. Guest profile synchronization is disabled.

An anonymous Firebase Authentication identity may still be used in the background for managed AI access, usage limits and related technical services. This technical identity is distinct from signing in to an optional user account.

An optional verified account allows access to account-based features, including Arena. Supported sign-in methods may include email/password, Apple and Google, depending on the app version and enabled service configuration. Competing in Arena requires a verified account; merely having a background anonymous Firebase identity does not grant Arena access.

Before AI content or usage analytics is transmitted, the app presents its data-sharing disclosure and requests consent. Optional account/profile disclosures and push notification opt-in are separate decisions. If the required AI/analytics disclosure changes materially, the app may request consent again.

## 3. AI requests and information sent to Google

SprachCoach offers two ways to use Google's Gemini models:

- **Included managed AI:** Requests are made from your device using Firebase AI Logic, with Firebase Authentication and Firebase App Check for supported operations.
- **Bring Your Own Key (BYOK):** If you supply your own Gemini API key, requests use Google's Gemini API with that key.

Only information needed for the feature you invoke is sent to Google. Depending on the feature, it can include microphone audio during a live conversation, speech or conversation transcripts, text you enter, writing answers, dictionary or vocabulary requests, custom coaching instructions, and images you explicitly capture or select for analysis. If you request feedback on a saved conversation or an oral exam, the relevant transcript may be submitted for that evaluation.

If you choose first-name personalization, **only the first name** is added to Gemini conversation instructions for a greeting. Your surname and username are not included for that purpose.

SprachCoach's own backend can supply AI configuration, enforce included-AI allowances and record pseudonymous usage or quota metadata. **It does not act as a proxy for, or store copies of, your AI prompts, microphone audio streams, photos, conversation transcripts or model responses.** Those AI materials are sent to Google for processing, not to the developer's analytics server.

For BYOK, your API key is stored in protected device storage (iOS Keychain or Android Keystore-backed storage). The key is not uploaded to the SprachCoach server. You can replace or remove it in Settings; an application update does not intentionally delete or replace it. BYOK uses your own Google API access and is subject to the applicable Google terms and quota.

Google determines its own processing and retention practices according to the Google services, account and terms involved. SprachCoach does not claim that Google never retains AI content or never uses it for its own purposes. Consult [Google's Privacy Policy](https://policies.google.com/privacy) and the [Gemini API terms](https://ai.google.dev/gemini-api/terms).

## 4. Technical, analytics and included-AI usage data

With the applicable consent, the app sends pseudonymous operational and usage information to a developer-operated server. Depending on your activity, this can include:

- A randomly generated installation ID and a Firebase UID used to associate authorized operations;
- App launches, screens viewed, interactions and feature usage;
- AI request and session successes, failures, approximate durations and usage counters;
- Platform, operating system, app/build and update versions, device model, locale and related technical metadata;
- Selected learning or explanation language, CEFR level, AI access mode and consent version/time;
- Whether a custom coaching instruction is configured, **not its text**.

These identifiers do not themselves contain your name, email address, advertising ID or device serial number. However, they are **pseudonymous, not guaranteed anonymous**: where an account or verified device link exists, the developer's systems may be able to associate records with that account.

The developer's analytics service is not intended to collect dictionary search words, microphone audio, AI prompts or responses, photographs, saved conversation or exam transcripts, private writing answers, custom coaching instruction text, or BYOK API keys.

Usage data helps operate included-AI limits, diagnose reliability, detect abuse and understand use of the app. SprachCoach does not sell this information, use it for third-party advertising or cross-app advertising tracking, or use your AI content to train a developer-owned AI model.

## 5. Optional accounts and profile information

If you register or link a verified account, Firebase Authentication and the selected sign-in provider process the information required to authenticate you. With email/password, Firebase processes the email address, password authentication, email verification and account-recovery operations. Apple or Google sign-in may provide account identifiers and suggested profile information for you to review.

The SprachCoach server may store the Firebase UID, authentication provider, verification status/date, the consent version/time for account or profile features, and associations between separately verified app installations and the account. Passwords are not sent to, or stored by, the SprachCoach analytics server.

When you explicitly create or complete a server-side account profile, the server may store your **username, first name and optional last name**. A guest's locally entered names and username are not synchronized as a guest profile.

Your username is also the **public Arena name**, displayed as `@username` in participating matches and rankings after the applicable profile/public-visibility disclosure and choices. First and last names are not displayed in the public Arena rankings. A username must be unique; the app may check its availability with the server.

Existing unrelated Firebase identities are not merged automatically. Creating or linking an account does **not** automatically upload or synchronize your private Grammar, Vocabulary, Writing, Listening, Reading or speaking history, transcripts, saved words or Gemini API key. These continue to be stored locally unless you deliberately export or share them.

## 6. Arena, social features and weekly rankings

If you choose to participate in Arena, the SprachCoach server processes the information needed to run and protect account-based competitions. This may include your account UID, public username, Arena participant identifier, CEFR band or competition eligibility, friendships and friend requests, invitations, blocks, user reports, match registrations, submitted answer options, attempt timestamps, scores, results and integrity or moderation records.

Other participants may see your public username, relevant match/opponent information and results in the features in which you participate. Arena's **Weekly Champions** ranking may show participating users' public usernames, positions and scores. You can manage the available Arena participation and leaderboard-visibility choices in the app; changing visibility does not necessarily delete historical match or moderation records.

The weekly ranking window starts again on **Monday at 00:00 UTC**, but prior verified match results may remain in server history. Public waiting-player counts are aggregate figures and do not identify individual people. In-app Arena invitations do not by themselves grant another user access to your private device learning content.

Arena results and account-related competition records may remain linked to your verified account across devices. In contrast, personal learning history and locally earned learning progress are not automatically synchronized to the server merely because you participate in Arena.

## 7. Feedback, support and optional notifications

If you submit feedback, SprachCoach stores its category, title, messages, status and associated pseudonymous app/Firebase identity on the developer-operated server so that support can respond. Before an administrator first opens a ticket, the original request may be editable or deletable. Once viewed or answered, the thread may be retained as a support record; further replies may be available while the ticket remains open. Avoid including passwords, API keys or sensitive personal information in support messages.

Push notifications are **optional**. If you opt in, the app may register an Expo push token, notification preference and associated installation information with the developer-operated server. Notification titles, bodies and routing information are processed by Expo Push Service and the relevant platform delivery service: Apple Push Notification Service (APNs) or Firebase Cloud Messaging (FCM).

A notification about a support reply does not expose the private text of that reply on the lock screen; the app retrieves the support conversation when opened. You can disable notifications in the app or in your device's system settings. Some disabled-token and delivery records may be retained temporarily for operational purposes.

## 8. Information stored locally; exports and backups

SprachCoach stores learning and app data on your device. Depending on what you use, this includes conversation histories and feedback reports, dictionary searches and saved words, vocabulary sets and practice attempts, grammar quizzes and progress, reading/listening/writing work, local learning statistics and XP, preferences and custom instructions, consent records, cached service settings, and your optional BYOK key in protected storage.

Supported local information can be removed using the app's available controls. Uninstalling generally removes app-specific learning storage, but files you have exported outside the app and some system-managed credentials or backups may be retained independently under the operating system's rules.

You may explicitly share a local text export with another app, file location or recipient. Such an export may contain sensitive learning information, and the destination you choose controls its subsequent handling. This text export is **not** an automatic cloud backup and cannot simply be re-imported as a learning restore.

Where available, you may also create an **encrypted, user-managed learning backup file** protected by a separate recovery code. Restoring requires the same verified account and an empty eligible learning profile; automatic merging is not supported. Keep your recovery code separate from the file: the developer cannot recover a lost code. Backups are not automatically uploaded to a SprachCoach cloud-sync service. Local learning can be lost if you remove the app or change devices without a usable backup.

## 9. Permissions and third-party services

The app requests device permissions when relevant to a feature: microphone for voice practice, camera or photo-library access when you choose image analysis, and notification permission when you opt in. These permissions can be changed in your device's settings.

Services that may process information in connection with SprachCoach include:

- **Google LLC:** Gemini API, Firebase AI Logic, Firebase Authentication, Firebase App Check and, for Android notifications, FCM.
- **Apple:** optional Sign in with Apple and Apple Push Notification Service on iOS.
- **Expo / Expo Application Services:** optional notification delivery and app update distribution.

These providers may also process technical connection information such as IP addresses and service-request metadata under their own policies. Processing may occur outside your country, subject to the applicable provider terms and transfer arrangements. For provider-specific details, consult [Google Privacy](https://policies.google.com/privacy), [Apple Privacy](https://www.apple.com/legal/privacy/) and [Expo Privacy](https://expo.dev/privacy).

## 10. How long data is kept

- **On-device learning data:** Generally remains until you remove it using the app's controls, reset eligible data or uninstall; independently exported files and device-managed backups are outside that deletion.
- **Developer-server records:** Account/device associations, Arena results and social or moderation records, pseudonymous analytics and quota records, feedback threads, audit/security records and notification history may be kept for service operation, security, support and legitimate follow-up. There is **currently no single fixed automatic deletion schedule** covering all these server-side records.
- **External providers:** Google, Apple and Expo apply their own retention rules to information processed by their services.

Withdrawing consent generally stops new consent-bound AI/analytics transmissions; it does not automatically erase information already transmitted or remove account, Arena or support records. Where data deletion is requested, some records may need separate review due to account ownership, abuse prevention, legitimate retention requirements, third-party processing and shared competition history.

## 11. Access, consent withdrawal, export and deletion requests

You can withdraw the AI/analytics data-sharing consent through **Settings → Privacy & data**. Consent withdrawal restricts affected AI features and stops consent-bound analytics until you consent again. You can also manage your BYOK key, notification preference, local data controls and available Arena profile/visibility controls in the app.

For a verified account, Account settings may offer access to account or server exports, removal of supplementary account-verification/device-link metadata, and requests for **full erasure** or **export assistance**. Removing supplementary account metadata alone does not remove Firebase credentials, all Arena or analytics records, support history or on-device learning.

A full-erasure or export-assistance submission is a **request for review**, **not confirmation that deletion or export has occurred**. You may be able to check its status or cancel an eligible pending request. Verified deletion across affected systems is not an immediate self-service action; no data should be treated as deleted until the developer has confirmed the necessary processing.

You can contact **sekercideveloper@gmail.com** to ask about information held about you or to exercise applicable privacy rights. Depending on the laws that apply, those rights may include access, rectification, erasure, restriction, data portability, objection and withdrawal of consent. You may also have the right to complain to a competent data-protection authority. Identity verification may be needed before disclosing or changing account-associated records.

## 12. Why information is processed

SprachCoach processes information to provide the learning, AI, account and Arena features you request; operate included-AI quotas; maintain security, prevent abuse, investigate reliability problems; provide support; and deliver notifications that you enable.

Where EU data-protection law applies, the legal basis depends on the processing activity. The app requests consent for disclosed AI/analytics sharing and optional notification enrollment; account and Arena data are used to deliver features you choose, and some technical/security processing may be necessary to operate and protect the service. Consent can be withdrawn for consent-based processing without making earlier lawful processing retroactively invalid.

## 13. Security

SprachCoach uses encrypted network connections for supported network communications and platform-protected storage for BYOK keys. Firebase Authentication and App Check protect supported access flows, and user-owned account/Arena operations use verified identity controls. User-created encrypted learning backup files require a separate recovery code.

No method of storage or transmission is completely risk-free. Avoid putting sensitive personal data or credentials into AI prompts, feedback messages or publicly visible usernames.

## 14. Children

SprachCoach is not directed at children under 13 and does not knowingly seek identifying information from children under 13. If you believe a child has provided personal information, contact the developer so the situation can be reviewed. Different age-related requirements may apply in your jurisdiction.

## 15. Changes to this policy

We may update this policy when features, service providers or data practices change. If a change materially affects required AI content sharing or recipients, the app will update the relevant notice and request renewed consent where appropriate. The effective date at the top identifies this published version.

## 16. Contact

**SprachCoach — Privacy and data requests**  
**Email:** sekercideveloper@gmail.com

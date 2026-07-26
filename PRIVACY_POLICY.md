# SprachCoach Privacy Policy

**Effective date: July 2026**

> This document mirrors the privacy policy shown inside the app
> (Settings → Privacy & data → View privacy policy). Host it at a public
> URL (e.g. GitHub Pages) and enter that URL in App Store Connect →
> App Privacy → Privacy Policy URL.

## Overview

SprachCoach is a German-practice app that lets you hold spoken
conversations and analyze text from images with an AI tandem partner.
This policy explains what data the app handles, how it is collected,
what it is used for, and with whom it is shared.

## Data collected by the developer (Anonymous Usage Metrics)

SprachCoach has **no user accounts** and **does not collect any personal data**
(such as your name, email, location, device identifiers, audio files, images, or conversation content).

To help improve the stability and usability of the app, SprachCoach sends
**anonymous product interaction telemetry** to the developer's backend server.
This data is completely decoupled from your identity and includes only non-personal aggregate events:

- Button clicks and UI interaction counts,
- Voice call counts and call duration metrics,
- Event triggers when the image text analysis feature is used (e.g., "photo_analyzed" event counter).

**What is NEVER sent to the developer's backend:** Your Gemini API key,
microphone audio, camera photos, conversation transcripts, grammar reports, or any personally identifiable information.

## Data stored only on your device

The following stays entirely on your device and is never transmitted to or stored on the developer's server:

- Your Gemini API key (stored encrypted in the iOS Keychain),
- Your saved conversation transcripts and feedback reports,
- Your language and coaching-style settings,
- The record of your data-sharing consent.

You can delete each of these inside the app at any time; deleting the app
removes them all.

## Data shared with the Google Gemini API

To power its core AI features, the app sends data directly from your device
to Google's Gemini API, a third-party AI service operated by Google LLC.
This happens **only after you have given explicit consent in the app**,
and only in these situations:

- **During a live practice call:** Your microphone audio (your voice) and
  the live transcript of the conversation.
- **When analyzing text from a photo:** The photo you capture or select in the app containing German text, sent solely to extract, analyze, and explain vocabulary/grammar.
- **When you request feedback on a saved conversation:** That
  conversation's transcript.
- **If you have written custom coaching instructions:** That text, as
  part of the conversation setup.

**How it is collected:** The microphone is only active during an ongoing call,
and the camera/photo library is accessed only when you explicitly take or select a photo to analyze text. Photos and audio are processed directly by the Gemini API over an encrypted connection (TLS) using your provided API key. The developer never intercepts, sees, or stores your photos or audio.

Google processes this data as described in the [Google Privacy Policy](https://policies.google.com/privacy)
and the [Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms).

## Camera and Microphone Permissions

- **Microphone:** Used exclusively to enable real-time spoken German practice during active calls.
- **Camera / Photo Library:** Used exclusively to capture or upload images containing German text for AI analysis.

Both permissions are requested explicitly when you first use the respective features and can be revoked anytime in your iOS Device Settings.

## What the data is used for

- **AI Feature Data (Audio, Photos, Transcripts):** Used exclusively to run live voice conversations, analyze text from images, and generate requested feedback on your device.
- **Telemetry Data (Event Metrics):** Used exclusively for product analytics to monitor feature usage, app performance, and improve future app updates.
- **No Advertising or Profiling:** Data is never used for advertising, cross-app tracking, user profiling, or selling to third parties.

## Your consent and your control

The app cannot be used until you have read the data-sharing notice and
agreed to it. You can withdraw this consent at any time in
Settings → Privacy & data. You can also delete your API key, individual
saved conversations, and custom instructions at any time within the app.

## Data retention

- **Developer's Backend:** Retains only aggregated, anonymous usage event metrics. No personal or content data is retained.
- **On-Device Data:** Stored locally until you delete it or remove the app.
- **Google Gemini API:** For details on how long Google retains processed data, please refer to Google's terms linked above.

## Children

SprachCoach is not directed at children under 13, and the app does not
knowingly process children's data.

## Changes to this policy

If this policy changes in a way that affects what is shared or with whom,
the app will show the updated notice and ask for your consent again
before sending anything.

## Contact

Questions about this policy: ahmetcemaleddin@gmail.com

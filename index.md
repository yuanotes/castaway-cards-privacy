---
layout: default
title: Castaway Cards — Privacy Policy
---

# Castaway Cards
## Privacy Policy

> **Effective date: 2026-09-16 — Mixpanel integration**

### 1. Who is responsible and what this notice covers

This notice describes how **Brooklyn** (“we”) uses optional **Mixpanel** gameplay, playtime and performance analytics and basic error reporting in the PC game **Castaway Cards**, and handles privacy correspondence. We determine the purposes and means of this processing and act as the data controller where applicable law uses that term.

Privacy contact: **[yuanotes@gmail.com](mailto:yuanotes@gmail.com)**.

Steam’s own processing of accounts, purchases, payments, and platform services is described in the [Valve Privacy Policy](https://store.steampowered.com/privacy_agreement/), not by our Mixpanel integration.

### 2. Your choice

Analytics and error reporting are off by default for players. The Mixpanel SDK is initialized only after you expressly agree in the game and collection is enabled for that release. Declining or dismissing the initial prompt does not count as consent and does not prevent normal gameplay.

You can reopen the data collection options in the game settings and withdraw consent at any time. Consent is our basis for this optional processing. Withdrawal stops new reporting, clears the SDK’s pending local event queue, and disables the SDK. It does not automatically delete data already received, recall requests already sent, or affect the lawfulness of processing based on valid consent before withdrawal.

Your choice is stored on your device. You may continue playing without analytics; you do not need to supply an email address or SteamID to play. Earlier consent to GameAnalytics does **not** authorize Mixpanel: the updated game asks for a new choice.

### 3. Data collected

After consent, this integration may process:

- **Gameplay information:** gameplay activity, progression, and outcomes, used to understand how the game is played and improve its design. Agreeing during a run does not backfill earlier gameplay events: run-progress tracking starts with the next run.
- **Playtime and session information:** event times, random session and event identifiers, and foreground running time from the moment of consent. Timing pauses while the application is in the background or suspended. Foreground menus and idle time are included; this is not a measure of continuous interaction or Steam’s official playtime. The game records periodic time increments and a best-effort session-end summary. Crashes, interrupted delivery and offline limits can make the data incomplete.
- **Identifiers and technical information:** an SDK-generated random identifier retained across sessions on the device, the consent-notice version, game and SDK versions, operating system and platform, device model, screen dimensions and density, and network connection type. Receiving servers process the IP address associated with network requests. We disable the SDK option to use the client IP address for geolocation; this does not hide that address from the receiving service or remove its operational network logs.
- **Performance information:** foreground frame-rate samples, average FPS and low-frame-rate sample counts to assess smoothness.
- **Basic error information:** Unity error, exception, warning, and assertion messages, together with available stack traces. The game limits this reporting to 10 events per launch, including warnings. Message and stack-trace lengths are limited. This is not comprehensive capture of every error or native desktop crash.

Our custom events do not intentionally send SteamIDs, real names, email addresses, screenshots, session recordings, full save files, card-instance identifiers, or gameplay random seeds. The integration does not create Mixpanel People profiles or link an analytics identifier to a Steam account. Random identifiers can still link activities across sessions on a device, so this data **must not be described as entirely anonymous**. Error text and stack traces can contain runtime paths or other context; we cannot guarantee that they contain no personal information.

The game does not integrate Sentry or enable session replay.

### 4. Purposes and recipients

We use this information to understand gameplay and progression, analyze playtime and return patterns, improve game design, assess performance, diagnose errors, and improve stability. We do not use this integration to deliver targeted advertising or sell the analytics data described here.

Recipients are **Mixpanel** and its authorized service providers. Mixpanel acts as our processor for game analytics under its [Data Processing Addendum](https://mixpanel.com/legal/dpa/). Its [subprocessor list](https://mixpanel.com/legal/subprocessor-list/) describes providers involved in delivering the service. Mixpanel’s separate processing of developer accounts and website visitors should not be confused with our game analytics.

If you email us, we process your email address, message, and any attachments you choose to send in order to respond and handle your request. Correspondence is processed through Gmail/Google’s email service. Please do not send passwords, payment details, or unnecessary sensitive information.

### 5. Storage, retention, and international processing

Our Mixpanel project uses **United States data residency**. Mixpanel may process data outside your country or region. The Data Processing Addendum describes applicable transfer safeguards, including the Data Privacy Framework and Standard Contractual Clauses. A hosting-region choice does not by itself mean that all processing or access is confined to your country. Data protection rules vary between jurisdictions. You can decline or withdraw consent if you do not want this optional processing.

Our project was created on September 16, 2026. Mixpanel’s published [Data Retention Policy](https://docs.mixpanel.com/docs/privacy/gdpr-compliance#data-retention-policy) provides the following standard event-data retention for projects created after September 1, 2025:

| Data category | Published standard retention |
| --- | --- |
| Game analytics events | 2 years from the event date |

Applicable contractual terms or a configured shorter retention period may differ. These provider periods are not promises that withdrawal immediately deletes data, and should not be confused with dashboard date ranges. We do not create People profiles or collect Session Replay recordings, which have separate provider retention rules. We handle deletion requests under applicable terms and law; legally required records and results that can no longer reasonably identify a person may follow different arrangements.

The SDK stores its random identifier and pending authorized events locally. During normal operation, unsent authorized events can be retried on a later launch while consent remains valid; delivery is not guaranteed, particularly after a long offline period. On withdrawal, we clear pending events, but retain the local random identifier and consent choice. If you agree again, future events can therefore be associated with earlier authorized activity; no activity from the period without consent is backfilled. Uninstalling the game may not remove all local data.

Earlier releases used GameAnalytics. Replacing that SDK does not delete records already received by GameAnalytics or stop an old installed release from operating under its previous consent. This updated integration does not send new events to GameAnalytics or copy its historical data into Mixpanel. Contact us about requests concerning those earlier records; the [previous notice](https://github.com/yuanotes/castaway-cards-privacy/blob/a515ce2922e256e9c523d4dba7d431bc1d2ca236/index.md) describes that processing.

Privacy correspondence is retained for as long as needed to handle the request and necessary follow-up, or as needed for disputes or legal obligations.

### 6. Your rights and contact

Depending on applicable law, you may have rights to access, correct, delete, restrict processing, obtain portable data, object to processing, and complain to a data protection authority. You can always withdraw consent for these optional analytics in the game.

Contact **[yuanotes@gmail.com](mailto:yuanotes@gmail.com)** to make a request. We may ask for necessary version, platform, or locally stored analytics identifier information to verify the request and locate records. Because analytics use random identifiers, an email address or SteamID alone may not identify those records. We will explain what information is needed and work with the relevant provider as required by applicable law. Please do not post personal data in public GitHub issues.

If you have not reached the age at which you can independently consent to this processing under local law, do not enable analytics yourself. A parent or guardian can contact us with questions about children’s data or deletion requests. The game currently has no age-identification or parental-verification feature; its general consent button does not replace any additional authorization procedures required by law.

### 7. This policy website

GitHub Pages hosts this website. The page itself embeds no Mixpanel, advertising, third-party fonts, or analytics scripts. GitHub processes network information needed to serve the page, such as IP addresses. See the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) for its practices.

### 8. Changes

We will update this notice and state its effective date when the game’s data practices change. Where renewed consent is required, we will request it before starting the relevant collection.

# RetroPet — Privacy Policy

**Effective date:** 15 August 2026

This Privacy Policy explains what data the RetroPet mobile app ("RetroPet", "we",
"us") collects, why, and your choices. By using RetroPet you agree to this policy.

## Who we are / contact

RetroPet is operated by the app's publisher. For privacy questions or data
requests, contact: **midwayofdraenor@gmail.com**

## What we collect and why

We collect only what the app needs to function, plus optional diagnostics.

| Data | Examples | Why | Linked to you? |
|------|----------|-----|----------------|
| Account | Email address, username, hashed password; if you use social login, the account identifier and email provided by Apple, Google or Discord; your app language | Create and secure your account, sync your pet across devices, localize notifications | Yes |
| Gameplay | Pet state, life history, scores, collection, achievements, friends/connections | Provide the core game and social features | Yes |
| Purchases | In-app purchase / subscription status (via the App Store, Google Play and RevenueCat) | Deliver and restore purchases | Yes |
| Approximate location (optional) | Latitude/longitude while you search for nearby players | Match you with players within ~5 km. Held **in memory only** during your search and never stored | No |
| Product interaction | Events such as game played, pet evolved, screens viewed | Understand usage and improve the app (Firebase Analytics) | Yes |
| Diagnostics | Crash logs and performance traces (Sentry) | Find and fix crashes and slowdowns | No |
| Device push token | APNs/FCM token, Live Activity token | Send pet-care reminders and Live Activity updates (if you enable them) | Yes |

We **do not** sell your data, and we **do not** use it for cross-app or
cross-site tracking (no advertising identifiers). Our iOS Privacy Manifest
declares `NSPrivacyTracking = false`.

## Guests

You can play as a guest without an account. Guest data is stored on your device
and, if you later create an account, may be synced to that account.

## Nearby players (location)

The nearby-connection feature is optional and only works if you grant location
permission. While you search, your approximate coordinates are sent to our
server solely to match you with players within ~5 km. They are kept **in server
memory only for the duration of your search** — they are never written to our
database, never shared with other players (only relative distance is used), and
are discarded when you stop searching or disconnect. You can always connect by
QR code or through your friends list without sharing any location.

## Where data is processed

Account and gameplay data are stored on our backend (MongoDB) and processed by
the service providers below. Data may be processed in countries other than your
own; we rely on appropriate safeguards for any such transfers.

## Service providers

- **Apple App Store / Google Play** and **RevenueCat** — purchase processing and
  receipt validation.
- **Sign in with Apple, Google Sign-In, Discord** — optional social login. We
  receive your account identifier and email address from the provider you
  choose; we never see your password for those services.
- **Google Firebase (Analytics, Cloud Messaging)** — product analytics and push
  notifications.
- **Sentry** — crash and performance diagnostics.
- **Cloud hosting** — backend and database hosting.

Each provider processes data under its own privacy terms.

## Retention and deletion

We keep account and gameplay data for as long as your account exists. You can
**delete your account at any time** in **Settings → Delete Account**, which
permanently removes your account and associated pets, friends, connections and
purchase records from our backend. Diagnostic and aggregate analytics data that
cannot identify you may be retained.

## Your rights

Depending on your region (e.g. GDPR/UK GDPR, CCPA), you may have the right to
access, correct, export or delete your personal data, and to object to or
restrict certain processing. To exercise these rights, use in-app account
deletion or contact us at the address above.

## Children

RetroPet is **not directed to children under 13** (or the minimum age required
in your country). We do not knowingly collect personal data from children under
that age. If you believe a child has provided us personal data, contact us and
we will delete it.

## Security

Passwords are stored hashed, transport is encrypted (HTTPS), and access tokens
expire and refresh. No system is perfectly secure, but we take reasonable
measures to protect your data.

## Changes

We may update this policy. Material changes will be reflected by a new effective
date here and, where appropriate, an in-app notice.

# RetroPet — Privacy Policy

**Effective date:** 28 October 2026

This Privacy Policy explains what data the RetroPet mobile app ("RetroPet", "we",
"us") collects, why, and your choices. By using RetroPet you agree to this policy.

## Who we are / contact

RetroPet is operated by the app's publisher. For privacy questions or data
requests, contact: **midwayofdraenor@gmail.com**

## What we collect and why

We collect only what the app needs to function, plus product analytics and diagnostics.

| Data | Examples | Why | Linked to you? |
|------|----------|-----|----------------|
| Account | Email address, username, hashed password; if you use social login, the account identifier, email and name provided by Apple, Google or Discord (and your Google profile-photo link or Discord avatar); your app language, time zone and device platform (iOS or Android) | Create and secure your account, sync your pet across devices, localize notifications, keep your pet's night and reminder quiet hours on your local time, and count how many players use iOS or Android | Yes |
| Profile picture (optional) | A photo you choose from your device (not available to guests) | Shown with your username to other players (for example on your profile, in friends lists, user search and rankings) | Yes |
| Gameplay | Pet state, life history, scores, collection, achievements, friends/connections | Provide the core game and social features | Yes |
| Purchases | In-app purchase / subscription status (via the App Store, Google Play and RevenueCat) | Deliver and restore purchases | Yes |
| Location (optional) | Latitude/longitude while you search for nearby players | Match you with players within ~5 km. Held **in memory only** until you cancel the search, leave the Connect screen or disconnect, and never stored | Yes, while it is held |
| Product interaction | Events such as game played, pet evolved, screens viewed, with the app version and device platform; some events about playing with another player (a connection, a breeding or a visit to their pet) also include that player's user ID. Firebase may add the device model, OS version and an approximate area derived from your IP address | Understand usage and improve the app (our backend and Firebase Analytics) | Yes |
| Diagnostics | Crash logs and performance traces (Sentry), from the app and from our server | Find and fix crashes and slowdowns | Not the app's reports. Our server's reports may include the request being handled, such as your email address, account ID or IP address |
| Device push token | APNs/FCM token, Live Activity token | Send pet-care reminders and notifications about friends, breeding, achievements, the daily challenge and seasons (if you allow notifications), and Live Activity updates on iOS (on unless you turn them off in Settings) | Yes |
| Feedback (optional) | What you send with Send feedback: the message, the name and email you enter and any images you attach, plus the app version, device model, OS version and language the app adds | Read and answer your message, and fix what you report | Yes |

We **do not** sell your data, and we **do not** use it for cross-app or
cross-site tracking. We do not use advertising identifiers; on Android, Google
Firebase Analytics may collect your device's advertising ID (which you can reset
or delete in your device settings) and its Android ID. Our iOS Privacy Manifest
declares `NSPrivacyTracking = false`.

## Guests

You can play as a guest without creating an account. The app then creates a
guest account on our backend, linked to your device by a random identifier the
app generates. It holds your game data (such as your pet and your progress),
without an email or password. If you later create an account, your guest
account becomes that account and keeps your progress. If you sign in to an
existing account instead, your guest account stays on our backend as a separate
account, still linked to your device.

A guest account is kept and deleted like any other account (see "Retention and
deletion"): you can delete it in **Settings → Delete Account**. After logging
out, choosing to continue as a guest starts a new guest from zero and deletes
your device's previous guest account in the same way.

## Nearby players (location)

The nearby-connection feature is optional and only works if you grant location
permission. While you search, your coordinates are sent to our server solely to
match you with players within ~5 km. They are kept **in server memory only** —
they are never written to our database, never shared with other players (players
searching near you see only your username and how far away you are, to 0.1 km),
and are discarded when you cancel the search, leave the Connect screen or
disconnect. When you send a connection request to a nearby player, or receive
one, our server logs record the distance between the two of you (never your
coordinates). You can always connect by
QR code or through your friends list without sharing any location.

## Where data is processed

Account and gameplay data are stored on our backend (MongoDB) and processed by
the service providers below. Data may be processed in countries other than your
own; we rely on appropriate safeguards for any such transfers.

## Service providers

- **Apple App Store / Google Play** and **RevenueCat** — purchase processing and
  receipt validation.
- **Sign in with Apple, Google Sign-In, Discord** — optional social login. We
  receive your account identifier, email address and name (and your Google
  profile-photo link or Discord avatar) from the provider you choose; if you
  create your account this way, your starting username is based on that name,
  and other players can see your username. We never see your password for
  those services.
- **Google Firebase (Analytics, Cloud Messaging)** — product analytics and push
  notifications.
- **Apple Push Notification service** — Live Activity updates on iOS.
- **Sentry** — crash and performance diagnostics.
- **Cloud hosting** — backend and database hosting.

Each provider processes data under its own privacy terms.

## Retention and deletion

We keep account and gameplay data, and the feedback messages you send us, for
as long as your account exists. You can
**delete your account at any time** in **Settings → Delete Account**. This
permanently removes from our backend your account (username, email, password,
profile picture), your pets, friends and friend requests, connections, breeding
proposals, daily challenge scores and prizes, and the feedback messages you sent
us. Records you share with other players (friendships, connections, breeding
proposals) are deleted for them too, and their own records no longer point to
your account.

In our database, two kinds of records are kept after the deletion, with nothing
that identifies you:

- **Product analytics**: the in-app events the app sent to our backend (such as
  "game played"), and the day your account was created, are kept under a
  random identifier that is not linked to you or to any account, so that our
  usage statistics stay accurate. Each event is deleted at most 400 days (about
  13 months) after it was sent, and the creation day 400 days after that day.
- **Purchase records**: the store, the product, the date and the store's
  transaction number of each purchase are kept indefinitely, no longer linked to
  any account, to prevent fraud (the same purchase being redeemed twice) and to
  count our sales.

Crash reports from the app are not linked to you; reports from our server may
include the request being handled (such as your email address or account ID).
Our server logs, which can include your account ID, and any database backups
are kept by our hosting providers under their retention settings and are not
changed when you delete your account. Data held by our service providers (such
as Sentry and Firebase Analytics) is kept under their own retention settings.

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
expire and refresh. Our server keeps your IP address in memory for at most 30
minutes after your last request, to limit abusive request rates; it is not
stored in our database. Crash and performance reports that our server sends to
Sentry can include it. No system is perfectly secure, but we take reasonable
measures to protect your data.

## Changes

We may update this policy. Material changes will be reflected by a new effective
date here and, where appropriate, an in-app notice.

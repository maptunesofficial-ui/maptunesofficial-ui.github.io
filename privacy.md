---
title: Privacy Policy
permalink: /privacy/
---

# MapTunes Privacy Policy

**Draft under legal review. Effective date: to be set at launch.**
The operator's legal name and postal address will be added here before launch. To reach us, see [Support](../support/).

MapTunes gives turn-by-turn driving directions and can sing them over the music you are already playing. This policy says what data the
app uses, where it goes, and how long it is kept. It describes the app as it is built; when the app changes, this page changes first.

## The short version

- **No account.** There is no sign-up, no login, no profile, no email address.
- **No advertising and no tracking.** We do not sell or share your data for advertising, and we do not track you across other apps or
  websites.
- **Your route stays with you.** Your start, destination and searches go to the mapping provider that calculates the route. Our own
  server never stores them.
- **We never record or upload audio.**
- **Settings → Delete my data** removes what the app keeps on your phone and asks our server to forget your install.

## What stays on your phone

To navigate, MapTunes keeps these on your phone:

- places you saved (Home, Work and others) and recent searches;
- your route preferences (for example, avoiding tolls) and your Settings choices;
- a record of recent trips used to improve directions: how many turns, how many were sung or spoken, and timings, **never the route
  itself**;
- a small file that lets an interrupted trip resume;
- caches of song information (lyric timing, the artist's voice type) and of recent spoken or sung directions;
- a **random install number** and, where your iPhone supports it, an **Apple App Attest key** (see "Limits and security").

## What is sent while you drive

**To sing a direction**, the app sends our server the words of that direction (which can include a street name, a road number or an
exit) and facts about the song playing: its musical key, tempo, energy, the artist's voice type, and the timing of its lyric lines (with
their words, or only their syllable counts). It also sends the random install number and a random number for the trip, used only for the
limits below. **To look up a song**, our server receives the song's title and artist.

Our server passes these to the machines that make the sung clip and to our music-data provider. **It keeps none of them**: its logs
record lengths and scrambled codes, not street names or song titles. The machines that make a sung clip delete it, and the request
that made it, as soon as it has been sent back; a request queued at our GPU provider expires within 30 seconds.

If you switch **sung directions off** in Settings, no direction is sent to be sung; directions are spoken by your phone.

## Routes and search

To calculate a route and to search for places, the app sends your current position, your heading, your destination and your search text
to a mapping provider: **Stadia Maps** (routes built on OpenStreetMap data) and/or **Apple Maps** (Apple's MapKit, for the map, place
search and, where enabled, the route itself). They receive this directly from your phone or through our server; **we do not store it**.
Directions that come from Apple Maps are used only for the trip in progress and are not kept after it.

## Your music

MapTunes learns which song is playing from Apple Music's now-playing information, or, if you allow the microphone, from Apple's
ShazamKit, which identifies the song on Apple's systems. **MapTunes never records, stores or uploads audio.**

## Trip statistics (only if you switch them on)

If you switch on **Settings → Share trip statistics**, the app sends counts from each trip (how many turns, how many were sung or spoken,
timings) with the day's date, and **nothing that identifies you, your device or your route**. These rows carry no identifier, so they
cannot be looked up or deleted per person. They are kept only in our hosting provider's logs and are deleted automatically within 90 days.
Switching it off stops any further sending.

## Sharing your arrival time (only when you tap Share)

**Share** opens your iPhone's share sheet with your expected arrival time; you choose who receives it. If you share a **live link**, our
server keeps, **in memory only**, that expected arrival time and a random link number: **not your location, your destination or any name**.
Anyone with the link sees only that time. The link ends, and the server forgets it, when you tap **Stop sharing**, when the trip ends, or
at the latest 30 minutes after its last update or 12 hours after it was made.

## Subscriptions

MapTunes is a subscription with a free trial; Apple handles payment, the trial (one per Apple ID), renewal and cancellation. To check
whether your subscription is active, the app uses **RevenueCat**, which receives the random install number and Apple's purchase
receipt: no name, no email, no location. We do not receive your payment details.

## Crash reports

When crash reporting is on, **Sentry** receives a crash's technical details: the error, the app version, and the device model and iOS
version. The app removes locations, web addresses' details, keys and the user field before a report leaves the phone, and sends no
screenshots and no record of what you tapped.

## Limits and security

To stop abuse, our server keeps **in memory**, for up to a day, how many sung clips each install has asked for (keyed by the random
install number or the App Attest key), and the **App Attest public key** of each install, deleted after 90 days unused. App Attest lets
our server check that a request comes from the genuine MapTunes app. These identifiers are used only for these limits and for security.
**Delete my data** asks our server to forget both for your install.

## Who processes data for us

| Provider | What for | What it receives |
|---|---|---|
| Railway | hosts our server and its logs | the direction and song facts above, in transit; trip-statistics rows, if on; the in-memory limits and live links |
| RunPod | the machines that make sung clips | the direction and song facts for that clip; nothing is kept |
| FreqBlog | song information (key, tempo, lyric timing), via our server | the song's title and artist |
| Wikidata | the artist's voice type, via our server | the artist's name |
| Stadia Maps | routes and place search | your position, heading, destination and search text |
| Apple | the map, place search and, where enabled, routes (MapKit); song recognition (ShazamKit); App Attest; subscriptions | as Apple's own privacy policy describes |
| RevenueCat | subscription status | the random install number and Apple's purchase receipt |
| Sentry | crash reports, when on | the crash's technical details above |

None of them receives your install number or App Attest key except our own server (for the limits) and RevenueCat (for subscriptions).

## How long data is kept

| Data | Where | How long |
|---|---|---|
| Saved places, recents, settings, trip records | your phone | until you delete them or the app (Delete my data removes them) |
| Direction words, song facts, route requests | in transit | not stored by us |
| Trip statistics (if on) | hosting provider's logs | deleted automatically within 90 days |
| Sung-clip counts per install | our server's memory | up to a day; cleared by Delete my data or a server restart |
| App Attest public key | our server's memory | 90 days unused; cleared by Delete my data |
| Live arrival-time link | our server's memory | until you stop sharing or the trip ends; at most 12 hours |
| Subscription status | RevenueCat | under RevenueCat's terms |

## Your choices and rights

- **Delete my data** (Settings) removes the app's data from your phone and asks our server to forget your install.
- Switch **sung directions** or **trip statistics** off at any time in Settings.
- Location, microphone and Apple Music access can be changed in your iPhone's Settings.
- Depending on where you live, you may have further rights over your data. Contact us through [Support](../support/).

## Children

MapTunes is a driving app and is not directed to children under 13. We do not knowingly collect data from children.

## Changes

When this policy changes, the new version is posted on this page with its date.

---
title: Mane Privacy Policy
---


**Last updated: 4 October 2026**

Mane is a hair styling app for men. This policy explains what happens to your
information. It is short because Mane collects very little.

## The short version

- Mane has no accounts. You never give us a name, an email, or a password.
- Your hair profile, your photos, and your product log are stored **on your
  phone**, not on our servers.
- Your photos and your onboarding answers are sent to an AI service to produce
  your hair analysis. They are not stored there beyond a short retention window,
  and they are never used to train AI models.
- To keep the free AI features fair and affordable, our server counts how many
  times each install has used them, using a random ID the app makes up. That ID
  is not linked to your name, your Apple ID, or anything else about you. To stop
  automated abuse it also keeps a short-lived daily count per network, which
  never contains your IP address.
- We do not use analytics, advertising, or tracking of any kind.
- We never sell your information. There is nothing to sell.

## What Mane stores on your device

All of the following stays in Mane's private storage on your phone:

- **Your answers** to the onboarding questions (how your hair behaves, how it
  feels, what bothers you)
- **Your photos** (front, side, top), saved inside the app's own storage
- **Your hair analyses**, kept as a history so you can see how your profile
  changes over time
- **Your product log** — products you have tried, your ratings, and your notes
- **Your product evaluations**

We cannot see any of it. It is not backed up to us, synced to us, or accessible
by us. It may be included in your device's own backups (for example iCloud),
which are controlled by you and your device maker, not by Mane.

## What leaves your device, and why

Three features require sending information off your phone:

**1. Hair analysis.** When you ask Mane to analyze your hair, your three photos
and your onboarding answers are sent to our server, which forwards them to
**Anthropic's Claude API** to generate your profile. The result comes back and
is saved on your phone.

**2. Product evaluation.** When you ask whether a product suits you, the product
photo or the name you typed, plus a summary of your hair characteristics, is
sent the same way.

**3. Refreshing your picks.** When you ask for new recommendations, a summary of
your hair profile and your product log (the products you tried, your ratings,
the reasons you picked, and any notes you wrote) is sent the same way.

Our server does not store any of this content. It holds the request in memory
only for as long as the request takes and writes none of it to a database or
disk.

## The one thing our server does keep: usage counts

Each AI feature has a free allowance per install (for example, a set number of
hair analyses). To enforce it, the app creates a **random install ID** the first
time you use an AI feature and sends it with each request. Our server stores:

- that random install ID,
- how many times it has used each AI feature, and
- when it was first seen.

That is all. It contains no photos, answers, profile, log, or notes, and it is
not linked to your name, email, Apple ID, or device hardware. We use it only to
apply the allowance, never for tracking or advertising.

To stop automated abuse, our server also counts how many AI requests arrive
from each network per day. It does **not** store your IP address. It stores a
scrambled code (a keyed hash) made from the network address and that day's
date: it can't be turned back into the address, and the same network gets a
different code each day. These daily counts are deleted after about a day.

The install ID is kept in your iPhone's secure storage (the Keychain) so that
deleting and reinstalling the app does not reset the allowance. iOS may keep it
after the app is deleted.

Like most online services, our hosting provider also keeps standard technical
request logs (such as IP address and time of request) for a limited period, for
security and to keep the service running. We do not use them to identify you.

## The third party

Anthropic (the Claude API) processes your photos and answers to generate the
analysis. According to Anthropic's published policies:

- **Your data is not used to train their models.** Anthropic states: "We do not
  use API data for training."
- **Inputs and outputs are automatically deleted within 30 days.** Longer
  retention applies only if content is flagged for violating their usage
  policies.

Anthropic's privacy documentation is at https://privacy.claude.com.

We also use **Supabase** to host the server code described above and the usage
counts. It stores no photos, answers, profile, log, or notes.

## Shopping links

Some product recommendations include a link to buy the product. Tapping it opens
that retailer's site in your browser, and their privacy policy applies from that
point. Mane does not share any information about you with the retailer. We may
earn a commission on purchases made through these links in future.

## Deleting your data

Because your profile, photos, log, and evaluations live on your phone,
**deleting the Mane app deletes all of them**, permanently and immediately.
There is no server-side copy of them.

Two small things outlast the app: the random install ID in your iPhone's
Keychain, and its usage counts on our server. Neither contains anything about
you, and because the ID is not linked to you, we cannot tell which record is
yours unless you give us the ID.

The photos and answers already sent for analysis are deleted by Anthropic on the
schedule described above; we cannot delete them sooner on your behalf.

## Health and medical

Mane is a cosmetic styling app. It does not diagnose, treat, or give medical
advice, and it is not a medical device. If you have a concern about your scalp
or hair loss, see a dermatologist.

## Children

Mane is not directed at children under 13, and we do not knowingly collect
information from them.

## Your rights

Depending on where you live, you may have rights to access, correct, or delete
personal information held about you. In Mane's case, you hold your hair data
directly on your device and can delete it by deleting the app. The only thing on
our server is the anonymous usage count described above. If
you have a question about this, contact us at the address below.

## Changes

If this policy changes, the updated version will be posted here with a new "last
updated" date. Material changes will be noted in the app.

## Contact

Questions about this policy or your data: **support.mane.app@gmail.com**

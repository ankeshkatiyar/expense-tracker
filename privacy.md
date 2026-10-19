---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

<p class="muted">Last updated: {{ site.last_updated }}</p>

**In short:** we collect only what the app needs to track your expenses and
sync them across your devices. We don't sell your data, show ads, use
third-party analytics or track you. You can export or delete everything at any
time from inside the app.

## 1. Who we are

{{ site.app_name }} ("the app", "we", "us") is developed and operated by
{{ site.owner_name }}, an individual developer based in India, who is the
**data controller** (or "data fiduciary") for your personal data.

Contact for any privacy question, request or complaint (also our grievance
officer): {{ site.owner_name }},
<a href="mailto:{{ site.support_email }}">{{ site.support_email }}</a>.

This policy applies to users everywhere the app is available. It is written to
meet India's Digital Personal Data Protection Act 2023 (DPDP Act), the EU and
UK General Data Protection Regulation (GDPR), and US state privacy laws such as
the California Consumer Privacy Act (CCPA/CPRA). Section 11 covers extra rights
that apply in some places.

## 2. What we collect and why

| Data | Why we use it | Legal basis (EU/UK) | Where it's stored |
|---|---|---|---|
| Email address | To create your account and sign you in with a one-time code | Contract | Supabase (our cloud provider) |
| Password (only if you set one) | To let you sign in without an email code. Stored only as a secure one-way hash; we can never see it | Contract | Supabase |
| Name and username | To show your profile and let family members find you | Contract | Supabase |
| Expenses and income you add or import (amount, category, merchant, date, notes, tags) | To provide the app's features | Contract | On your device and in Supabase |
| Receipt photos you attach | To keep a copy of your bills | Contract | On your device and in Supabase Storage |
| Trip documents (tickets, bookings, IDs) you upload | To keep your travel documents with your trip | Contract | Supabase Storage; shared only with family members you share the trip with |
| Budgets, custom categories and recurring payments | To sync them across your devices | Contract | On your device and in Supabase |
| Push notification token for each signed-in device (from Apple or Google) | To send you family and trip invites and trip activity. Removed when you sign out or turn off "Invites & activity" | Contract | Supabase; messages are delivered through Apple Push Notification service or Firebase Cloud Messaging |
| Crash and performance diagnostics (from Apple's MetricKit on iPhone/iPad, and the app's own crash reporter on Android) | To find and fix bugs | Legitimate interest (keeping the app working) | Supabase |
| Currency, theme and app-lock preferences | To remember your choices | Contract | On your device only |

We collect this data only from you and your device. We don't buy data or
receive it from other companies.

**Bank SMS:** the app only processes bank messages you choose to give it:
text you paste or share, or messages passed by a Shortcuts automation you set up
on iPhone. The app does not ask for SMS permission and never reads your
messages on its own. The original message text is never stored or uploaded,
only the details taken from it (amount, merchant, date) plus a one-way
fingerprint used to avoid logging the same message twice.

**Shared trip links:** if a trip owner taps **Share link**, anyone who has that
link can see a read-only summary of the trip on our website: its name and
dates, the display names of the people on it, the trip's expenses (merchant,
category, amount, date, who paid) and who owes whom. It shows nothing else
from your account. The link stays secret unless you share it, and the trip
owner can stop sharing at any time, which makes the link stop working.

**Face ID / fingerprint / passcode:** if you turn on app lock, it is handled
entirely by your phone's operating system (iOS or Android).
We never receive biometric data.

**What we don't do:** we do not sell or rent your personal data, "share" it for
cross-context behavioural advertising, show ads, use third-party analytics or
advertising SDKs, track you across other companies' apps or websites, or make
automated decisions that have legal or similarly significant effects on you.

## 3. Family sharing

Family sharing is optional. If you join a family, its members can see your
name, your username, your expenses (except ones you mark "Hide from family")
and receipts attached to expenses they can see. You choose who to invite or
which invite to accept. If you leave the family, they lose access straight away.

## 4. Who we share data with

We share personal data only with service providers that process it on our
behalf and under contract, to run the app:

- **Supabase Inc.** (USA): database, file storage and sign-in. Your data is
  stored in Supabase's **Mumbai, India (ap-south-1)** region.
- **Google LLC (Gmail SMTP)** or another transactional email provider: sends the
  one-time sign-in codes to your email address.
- **Apple Inc.**: app distribution on iPhone and iPad, crash reports through
  MetricKit, and Face ID if you enable it.
- **Google LLC**: app distribution on Android through Google Play, and
  fingerprint/face unlock if you enable it. If your phone's Android backup is on,
  Google backs up the app's local data (but never your sign-in session).

We may also disclose data if required by law, to respond to a valid legal
request, or to protect the rights and safety of our users or others. If the app
is ever transferred to a new owner, your data would move with it under this
policy, and we would tell you in advance.

## 5. International transfers

The app is run from India and your data is stored in India. If you use the app
from another country, including the EU, UK or US, your data is transferred to
and processed in India, and service providers may access it from the USA.

For transfers from the EU, UK or Switzerland, we rely on the European
Commission's **Standard Contractual Clauses** (and the UK addendum) included in
our providers' data processing terms, together with the security measures in
section 7. You can ask us for more information about these safeguards.

## 6. How long we keep data

- **Your account and app data:** until you delete it or delete your account.
- **After you delete your account:** your account, expenses, settings, family
  membership and receipt photos are deleted from our live servers. Any copies in
  our provider's backups are overwritten as part of its normal backup cycle.
- **Diagnostic reports:** contain no expense data. When you delete your account
  they are unlinked from you, and all reports are deleted after 12 months.
- **Support emails:** kept for up to 2 years so we can follow up on your request.

## 7. Security

Data is encrypted in transit (HTTPS/TLS) and at rest by our provider. Database
rules make sure each user can access only their own data and the data their
family has chosen to share. Passwords are stored only as salted hashes. You can
add a Face ID, fingerprint or passcode lock in Settings. No system is perfectly secure; if a
breach affects your personal data, we will notify you and the relevant
authorities as required by law.

## 8. Your rights and choices

Wherever you live, you can:

- **Access and correct** your data in the app at any time.
- **Export (portability):** download all your expenses from **Settings → Export
  all as CSV**, or ask us for a copy of all your data.
- **Delete** your account and all its data from **Settings → Delete account**, or without the app as described on
  [Delete your account]({{ '/delete-account/' | relative_url }}).
- **Withdraw consent or object** to processing, for example of diagnostics.
- **Complain** to us, and we will try to resolve it.

To make a request, email
<a href="mailto:{{ site.support_email }}">{{ site.support_email }}</a> from the
email address on your account. We may ask you to confirm your identity. We
reply within 30 days (often much sooner) and don't charge for requests. We will
never treat you differently for using your privacy rights.

## 9. Children and teenagers

You must be at least **13 years old** to use the app. We do not knowingly
collect personal data from children under 13. If we learn that we have, we will
delete the account and its data. If you believe a child under 13 is using the
app, please contact us.

**If you are under 18**, or under the age of digital consent where you live
(for example 16 in some EU countries, 14 in South Korea), you may use the app
only with the permission of a parent or legal guardian, who should read this
policy with you. A parent or guardian can ask us to see, correct or delete
their child's data, or to close the account, by emailing us. Teenagers can also
delete their own account at any time in **Settings → Delete account**.

For users under 18 we collect only the data needed for the app to work, and we
never show ads, use third-party analytics, track them across apps or websites,
build behavioural profiles or sell their data.

**Family sharing for teenagers:** family members a teenager joins can see their
expenses (except ones marked "Hide from family"). We recommend that teenagers
join a family only with people their parent or guardian knows.

We will update how we collect parental consent as required by India's Digital
Personal Data Protection Rules, 2025, and other applicable laws.

## 10. Your choices on the device

- **Notifications:** turn them on or off in Settings or in your phone's settings.
- **App lock:** turn Face ID, fingerprint or passcode lock on or off in Settings.
- **Hide from family:** mark any expense as private.
- **Diagnostics:** you can stop crash reports by turning off *Share With App
  Developers* in iOS Settings → Privacy & Security → Analytics & Improvements.

## 11. Extra information for your region

### European Economic Area, United Kingdom and Switzerland

In addition to the rights in section 8, you have the right to **restrict**
processing and to **object** to processing based on legitimate interests. You
also have the right to lodge a complaint with your local data protection
authority (for example the ICO in the UK). We'd appreciate the chance to help
first, so please contact us.

We don't have a representative in the EU or UK. Please contact us directly at
the email above.

### India

You have the rights set out in the DPDP Act, including to access a summary of
your data, to correct and erase it, to nominate another person to exercise your
rights in case of death or incapacity, and to grievance redressal. Contact our
grievance officer at the email above. If you are not satisfied with our
response, you may complain to the Data Protection Board of India.

### California and other US states

In the past 12 months we have collected these categories of personal
information: identifiers (email, name, username, user ID), financial
information you enter (expenses and income), photos (receipts) and diagnostic
information, for the purposes described in section 2 and from the sources in
section 2. We have **not sold or shared** personal information (as those terms
are defined in the CCPA), including of anyone under 16, and we don't use or
disclose sensitive personal information for purposes that would give you a
right to limit it.

You have the right to know, access, correct and delete your personal
information, and the right not to be discriminated against for using these
rights. You may use an authorised agent to make a request on your behalf; we
may ask for proof of authorisation. Residents of other US states with privacy
laws (such as Colorado, Connecticut, Virginia, Texas and Oregon) have similar
rights and can contact us the same way. If we decline a request, you can
appeal by replying to our decision.

## 12. Changes to this policy

If this policy changes, we will update this page and the "Last updated" date.
For significant changes, we will also let you know in the app or by email
before they take effect.

## 13. Contact

{{ site.owner_name }}, India ·
<a href="mailto:{{ site.support_email }}">{{ site.support_email }}</a>

---
layout: default
lang: en
title: Privacy policy
alternates:
  en: /roku-sleep-timer/en/privacy.html
  pt: /roku-sleep-timer/pt/privacy.html
  es: /roku-sleep-timer/es/privacy.html
---

# Privacy policy

Effective date: {{ site.policy_effective_date }}

This policy explains what information the Roku Sleep Timer app ("the app") handles on Android and iOS. The app is made by an independent developer ("we") and is not affiliated with Roku, Inc.

## Summary

- We do not run servers and we do not have user accounts.
- Your Roku's details and your settings stay on your phone.
- The app sends usage statistics and crash reports to Google Firebase, tied only to a random identifier, so we can fix problems and improve it.
- The app shows ads through Google AdMob. Google may collect device identifiers and usage data to show and measure ads, as described below.

## Information stored on your phone

To turn your Roku off, the app saves on your phone:

- the IP address, name, model and serial number of the Roku you connected;
- your language choice;
- the end time of a running timer.

This information is stored only on your phone. It is sent only to your Roku, over your local network, and never to us. Tapping **Change** in the app's settings forgets the Roku, and uninstalling the app deletes everything.

## Communication with your Roku

The app finds Roku devices on your Wi-Fi network and sends them commands such as "power off" using Roku's External Control Protocol (local network, port 8060). This traffic stays inside your local network. As defined by Roku, it is not encrypted.

## Advertising (Google AdMob)

The app shows a full-screen ad when it opens. Ads are provided by Google AdMob, which may collect and process:

- device identifiers, such as the Android advertising ID or the iOS identifier for advertisers (IDFA, only if you allow tracking);
- your IP address and the approximate location derived from it;
- device and app information, such as model, operating system and app version;
- ad interactions, such as views and taps, plus diagnostic data.

Google uses this data to show ads, measure their performance, limit how often you see them and prevent fraud. Where the law requires it (for example in the European Economic Area, the United Kingdom and Switzerland), the app asks for your consent before showing ads, using Google's consent tool. When that applies, you can change your choice at any time in the app under **Settings > Privacy and ads**. On iOS, ads are personalized only if you allow tracking. You can also reset or delete your advertising ID in your phone's settings.

Learn more in [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites) and in [Google's privacy policy](https://policies.google.com/privacy).

## Usage statistics and crash reports (Google Firebase)

The app uses Google Analytics for Firebase and Firebase Crashlytics, provided by Google. They collect:

- how the app is used, such as the screens opened, timers started or cancelled, whether connecting to the Roku or turning it off worked, and whether the opening ad was shown;
- device and app information, such as model, operating system, language, app version and a random identifier for this installation;
- crash reports with the technical state of the app when it failed;
- the approximate location (country or region) derived from your IP address.

These statistics never include your Roku's IP address, name or serial number. We use them only to understand how the app is used, fix errors and improve it, and we do not use them to identify you or to show you ads. Google keeps analytics data for up to 14 months and crash reports for up to 90 days. Learn more in [Privacy and security in Firebase](https://firebase.google.com/support/privacy).

## Notifications

On iOS the app can schedule a local notification to remind you when a timer ends. It is created on your phone and is not sent through any server.

## What we do not do

- We do not sell your personal information.
- We do not collect your contacts, photos, precise location or files.
- We do not combine the usage statistics with other data to identify you.

## Children

The app is not directed to children under 13 and we do not knowingly collect information from them.

## Your rights

Depending on where you live (for example under Brazil's LGPD, the EU GDPR or California's CCPA), you may have rights to access, correct or delete personal data and to object to its processing. We do not hold data that identifies you: usage statistics are linked only to a random identifier, which is deleted when you uninstall the app. For data processed by Google for advertising, use the controls above or [Google's privacy tools](https://myaccount.google.com/data-and-privacy).

## Changes

If this policy changes, we will update the effective date above and publish the new version on this page.

## Contact

{% if site.contact_email != "" %}Email [{{ site.contact_email }}](mailto:{{ site.contact_email }}) or open{% else %}Open{% endif %} an issue at [{{ site.issues_url }}]({{ site.issues_url }}).

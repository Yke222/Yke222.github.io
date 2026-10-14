---
layout: default
lang: en
title: Support
alternates:
  en: /roku-sleep-timer/en/support.html
  pt: /roku-sleep-timer/pt/support.html
  es: /roku-sleep-timer/es/support.html
---

# Support

## Getting started

1. Connect your phone to the same Wi-Fi network as the Roku.
2. On the Roku, open **Settings > System > Advanced system settings > Control by mobile apps** and set **Network access** to **Permissive**.
3. Open the app, pick your Roku from the list or type its IP address (on the Roku: **Settings > Network > About**).
4. Choose a duration and tap **Start timer**. Then go watch YouTube or any other app on the TV.

Roku developer mode is not needed.

## Common questions

**The app says the Roku refused the command.** Network access under **Control by mobile apps** is set to **Limited** or **Disabled**. Change it to **Permissive**.

**My Roku does not show up in the list.** Some routers and iPhones block device discovery. Type the Roku's IP address instead.

**The Roku turned off but the TV stayed on.** Turn on HDMI-CEC on the TV. Brands call it differently, for example Anynet+ (Samsung), SimpLink (LG), Bravia Sync (Sony) or CEC (others).

**On iPhone the timer did not turn the Roku off.** iOS does not let apps send commands while in the background. Keep the app open: it keeps the screen on while the timer runs. If you leave it, a notification reminds you to come back.

**On Android the timer did not fire.** Check that the app is allowed to use **Alarms & reminders** in the system settings and that battery optimization is not restricting it.

## Contact

{% if site.contact_email != "" %}Email [{{ site.contact_email }}](mailto:{{ site.contact_email }}) or open{% else %}Open{% endif %} an issue at [{{ site.issues_url }}]({{ site.issues_url }}).

[Privacy policy](privacy.html) · [Terms of use](terms.html)

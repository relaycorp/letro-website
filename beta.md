---
permalink: /beta
nav_order: 1
---

# Beta testing

We're currently running an [invite-only](https://play.google.com/console/about/closed-testing/) beta testing programme to gather feedback on the initial version of Letro.

## Install Letro

1. [Join the beta testing programme](https://play.google.com/apps/internaltest/4700736795526212865).
2. Install Letro from the [Play Store](https://play.google.com/store/apps/details?id=tech.relaycorp.letro&hl=en-US&ah=p1C05uMiobvkkSCCAfeMRoorAxk).

## Important considerations

We're very grateful for your interest in Letro, but we need to be upfront about the risks of using it at this point:

- **Things will most certainly break**. We're confident that Letro is stable enough for daily use, but we're sure you'll uncover issues that the team hadn't come across yet.
- **You could lose your data at any time**, due to either a bug or a breaking change in a newer version of the app. If you share anything important, make a copy outside Letro.
- **We've requested an independent security audit from a reputable team**. We've taken every reasonable measure to ensure that Letro is secure, but you shouldn't take our word for it until the report is published. So, please don't use Letro for anything sensitive yet.

## Important limitations

Except for some minimal, non-sensitive metadata stored on [our server](https://docs.relaycorp.tech/letro-server/), all your data is stored on your own devices. This means that:

- Free account ids under Relaycorp-managed domain names (e.g., `applepie.rocks`, `cuppa.fans`) can't be migrated to other devices or restored if you uninstall Letro. This limitation doesn't apply to any VeraId-enabled domain names under your control.
- You _shouldn't_ use the same Letro account id across multiple devices. If you do this, each device would have a different set of contacts -- and you can't communicate with a contact you have on another phone, even if your id is the same.
- Conversations and contacts can't be migrated to other phones or restored if you reinstall Letro.

We have plans to address these limitations in the future in a privacy-respecting manner.

## Known issues

### Incoming data delays

Due to [a bug in Awala](https://github.com/relaycorp/relaynet-gateway-android/issues/717), incoming data may experience severe delays even when you're connected to the Internet. For example, you may try to create a free account and nothing happens for more than 10 seconds.

To check if this is the issue you're experiencing, open the Awala app. If you see a message saying "You're not connected to Awala", then you're affected by this bug.

To work around this issue, you can either:

- Switch to another network on Android (for example, from WiFi to 5G). You can revert this immediately.
- Force-stop Awala, then open Letro.

## Help and feedback

To report issues, get help or provide feedback, please contact Gus directly -- preferably via Letro, but email also works!
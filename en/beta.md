---
permalink: /beta
nav_order: 1
---

# Beta testing

Letro is now available for beta testing on Android! 🎉

<span class="fs-7 d-block text-center mx-auto">
[Install Letro](https://play.google.com/store/apps/details?id=tech.relaycorp.letro){: .btn }
</span>

## Important considerations

We need to be upfront about the risks of using it at this point:

- **Things will most certainly break**. We're confident that Letro is stable enough for daily use, but we're sure you'll uncover issues that the team hadn't come across yet.
- **You may lose your data at any time**, due to either a bug or a breaking change in a newer version of the app. If you share anything important, make a copy outside Letro.
- **We've requested an independent security audit from a reputable team**. We've taken every reasonable measure to ensure that Letro is secure, but you shouldn't take our word for it until the report is published. So, please don't use Letro for anything sensitive yet.

Also, please make sure to read our [Terms of Service](legal/tos.md) and [Privacy Policy](legal/privacy-policy.md).

## Important limitations

Except for some minimal, non-sensitive metadata stored on [our server](https://docs.relaycorp.tech/letro-server/), all your data is stored on your own devices. This means that:

- Free account ids under Relaycorp-managed domain names (e.g., `applepie.rocks`, `cuppa.fans`) can't be migrated to other devices or restored if you uninstall Letro. This limitation doesn't apply to any domain names under your control.
- You _shouldn't_ use the same Letro account id across multiple devices. If you do this, each device would have a different set of contacts -- and you can't communicate with a contact you have on another phone, even if your id is the same.
- Conversations and contacts can't be migrated to other phones or restored if you reinstall Letro.

We have plans to address these limitations in a privacy-respecting manner.

## Known issues

### Incoming data delays and duplicates

There are two separate bugs in Awala that affect Letro and any other compatible app **when the Internet is available**:

- Incoming data may experience severe delays when neither Awala nor Letro are running. As a temporary workaround, when you expect incoming data, keep Letro open.
- Incoming messages may be received twice. This can manifest as a reply received twice, or your chosen username having a random suffix appended, for example. There's no workaround for this.

We are working on fixing these issues in Awala.

### Reinstalling Awala requires reinstalling Letro

If you reinstall Awala or clear its data, you should also reinstall Letro or clear its data. This is a limitation in Awala itself.

## Help and feedback

To report issues, get help or provide feedback, please use [the r/Letro subreddit](https://www.reddit.com/r/Letro/).

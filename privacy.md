---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# Claude Admin — Privacy Policy

**Effective date:** 13 November 2026

This Privacy Policy explains what information the **Claude Admin** Discord bot (the
"Bot") handles, why, and what you can do about it. The Bot is run as a personal
project by an individual developer (the "operator", "we", "us"). It is not affiliated
with Anthropic or Discord.

## Summary

- The Bot runs on the operator's own computer. It has no public database, and it
  doesn't keep a log of every server message.
- Messages it receives, and data it reads on the operator's request, are sent to
  **Anthropic's Claude** AI model to generate replies and carry out tasks.
- We do not sell your data, use it for advertising, or share it with anyone else
  except as described below.

## 1. Information the Bot handles

**Messages sent to the Bot.** This covers direct messages from paired users and, in
servers where the operator has turned on listening, messages that @mention the Bot,
reply to it, or address it by name. In channels the operator has set to "all
messages", it covers every message there. For each message the Bot receives:

- the message text, and the name, type and size of any attachments;
- your Discord username and user ID;
- the message, channel and server IDs, the channel and server names, and the time
  it was sent.

**Information read on the operator's request.** In servers where management is
enabled, the operator can ask the Bot to read:

- message history in channels;
- member lists (usernames, nicknames, user IDs, roles, join dates and account
  creation dates);
- roles, channels and server settings;
- the ban list and the server audit log.

**Attachments.** Files are downloaded only when the operator's assistant requests
them. They are stored on the operator's computer.

**Configuration.** The Bot stores:

- the Discord user IDs allowed to control it;
- temporary pairing codes, which expire after one hour;
- the server and channel IDs it is configured for;
- automation settings, including scheduled message text and keyword patterns.

**Keyword alerts.** If the operator sets up an alert rule, a matching message's
first 300 characters and a link to it are sent to the operator by Discord DM.

**Moderation records.** Actions taken through the Bot are recorded by Discord in
the server's audit log, with a reason.

The Bot does not collect passwords, payment information, IP addresses, or data from
outside Discord.

## 2. How the information is used

We use this information only to operate the Bot:

- to reply to messages;
- to carry out server-management and moderation tasks the operator asks for;
- to run automations the operator has set up;
- to restrict control of the Bot to the operator.

## 3. Who receives it

- **Anthropic.** Messages and data processed by the Bot are sent to Anthropic's
  Claude model so it can understand requests and generate responses. Anthropic
  handles this data under its own terms and
  [privacy policy](https://www.anthropic.com/legal/privacy).
- **Discord.** The Bot runs on Discord, which handles all Discord data under its
  [Privacy Policy](https://discord.com/privacy).
- **Server staff.** The audit log, and anything the Bot posts, are visible to
  people in the server according to that server's permissions.
- **Legal requirements.** We may disclose information if the law requires it.

We do not sell or rent personal information, and we do not use it for advertising
or profiling.

## 4. Where it is stored and for how long

- Configuration is stored on the operator's computer until the operator removes it.
  Pairing codes expire after one hour.
- Downloaded attachments and the AI assistant's session history, which can include
  messages the Bot received or read, are stored on the operator's computer until
  the operator deletes them.
- Data sent to Anthropic is kept according to Anthropic's retention policies.
- Messages and audit-log entries on Discord stay on Discord under Discord's
  policies. Removing data from the Bot does not delete your messages from Discord.

## 5. Your choices and rights

- **Don't interact with it.** Where the Bot is mention-based, it only receives
  messages that address it. Ask your server's administrators how it is configured
  in your server.
- **Remove it.** Server administrators can remove the Bot at any time by kicking it.
- **Ask for access or deletion.** You can ask what data about you is stored on the
  operator's computer, or ask for it to be deleted. We will delete it there within a
  reasonable time. We cannot delete data held by Discord or Anthropic on your
  behalf. Contact them directly for that.

Depending on where you live, you may have more rights under local data-protection
law, such as the GDPR. Contact us to exercise them.

## 6. Children

The Bot is not directed at children. You must meet Discord's minimum age in your
country to use Discord and the Bot.

## 7. Security

The Bot's credentials are kept on the operator's computer, not in its source code,
and only allowlisted users can control it. No system is completely secure, and we
cannot guarantee the security of information sent over the internet.

## 8. Changes

We may update this policy. The effective date above shows when it last changed.

## 9. Contact

For privacy questions or requests, send a direct message on Discord to the Bot's
owner, or open an issue in
[this site's GitHub repository]({{ site.github.repository_url }}/issues). Don't post
personal data in a public issue.

See also: [Terms of Service]({{ '/terms/' | relative_url }})

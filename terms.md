# Terms of Service — Evil Bot

**Effective date:** November 4, 2026  
**Contact:** <me@mehdijai.com>

## 1. Acceptance

By adding, configuring, or using Evil Bot ("the Bot") in a Discord server, the server owner or authorized administrator agrees to these Terms of Service. The Bot is designed for use in Discord servers only and is not offered as a user-installed app or direct-message service.

## 2. Service description

Evil Bot sends messages for specific events at fixed dates or times hard-coded by the developer, in a Discord server channel selected by an authorized administrator, mentioning a role selected by that administrator. Administrators configure the destination channel and role, not the event schedule. Message delivery depends on Discord availability, the Bot's availability, and the relevant server permissions.

## 3. Permissions

Evil Bot requests the following permissions or command access to perform its functions:

- **View Channels:** access the configured channel.
- **Send Messages:** post scheduled messages.
- **Embed Links:** send embedded content when applicable.
- **Use Application Commands (slash commands):** allow authorized configuration and interaction.

The server must grant any permissions necessary for the Bot to function. Role mentions may also depend on Discord's role-mention settings and additional permissions; no successful ping is guaranteed.

## 4. Administrator responsibilities

The person configuring Evil Bot must have authority to do so in that server and must select an appropriate channel and role. Users must not use the Bot for harassment, excessive or unwanted pings, spam, or any activity that violates Discord's Terms of Service, Community Guidelines, or applicable law.

## 5. Data and privacy

Evil Bot stores only the Discord server (`guildId`), channel (`channelId`), and role (`roleId`) identifiers in Redis, as described in its separate Privacy Policy. It does not store per-server scheduling configuration. An authorized server administrator can run `/stop` to delete all three stored identifiers for their server and stop future event messages. By configuring the Bot, the server administrator acknowledges that these identifiers are needed to provide the service.

## 6. Availability and changes

The Bot is offered on an **as-is** and **as-available** basis. The developer may fix, modify, suspend, or discontinue it, including to address security issues, misuse, or Discord platform changes. Event messages may be delayed or missed during outages or interruptions.

## 7. Suspension or removal

The developer may restrict or discontinue access to the Bot when necessary to protect the service, other users, or Discord, or when these Terms are violated. Server administrators can run `/stop` to delete their server's configuration before removing the Bot. They may remove the Bot from their servers at any time.

## 8. Disclaimer and limitation of liability

To the extent permitted by applicable law, the developer makes no guarantee of uninterrupted operation, timely delivery, or suitability for critical notifications and is not responsible for losses resulting from service interruptions, missed notifications, or configuration errors. Nothing in these Terms excludes liability that cannot legally be excluded.

## 9. Changes to these terms

These Terms may be updated as the Bot evolves. The effective date above will be changed, and material changes will be communicated through an appropriate available channel. Continued use after an update constitutes acceptance to the extent permitted by applicable law.

## 10. Contact and reports

To request support, report misuse, or raise a concern about the Bot, contact: **<me@mehdijai.com>**.

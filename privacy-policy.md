# Privacy Policy — Evil Bot

**Effective date:** November 4, 2026  
**Contact:** <me@mehdijai.com>

## 1. Overview

Evil Bot ("the Bot") is a Discord server (guild) bot that posts messages for specific events at fixed times defined in its code. Messages are sent to a channel selected by a server administrator and mention a role selected by that administrator. Server administrators cannot create or edit event times through the Bot. The Bot does not provide direct-message or user-installed app functionality.

## 2. Information processed

To operate, the Bot stores only the following three identifiers for each participating server in a Redis database:

- **Discord server (guild) ID** — to identify the server.
- **Discord channel ID** — to know where to send scheduled messages.
- **Discord role ID** — to know which role to mention.

The Bot also receives the limited information Discord provides to execute configuration commands and send messages. It does not intentionally collect or store message histories, members' profiles, direct messages, email addresses, or passwords. A role mention is delivered through Discord; Evil Bot does not need to maintain a list of members assigned to that role.

## 3. How information is used

The stored identifiers are used only to select the server, channel, and role for event messages at the fixed, code-defined times. The Bot does not store per-server schedules or reminder settings. It does not use this information for advertising, profiling, or sale.

## 4. Sharing and third parties

Evil Bot communicates with Discord through Discord's API to deliver its configured functionality. The developer does not sell server configuration data or share it with advertisers or data brokers. Discord handles messages, mentions, and other information on its platform under its own policies.

## 5. Data retention and deletion

The three server configuration identifiers are stored until an authorized server administrator runs the `/stop` command, which deletes the server's `guildId`, `channelId`, and `roleId` from Redis and stops event messages for that server. For questions or assistance with deletion, contact the developer using the contact method below. Simply removing the Bot from a server is not described here as a data-deletion mechanism; use `/stop` before removal to delete the configuration.

## 6. Security

The developer takes reasonable measures to protect stored configuration data against unauthorized access. No storage or transmission system can be guaranteed to be completely secure.

## 7. Your choices

An authorized server administrator selects the channel and role and can delete the server's stored identifiers at any time using `/stop`. Event dates and times are defined by the developer, not by server administrators. Questions, requests to inspect the stored identifiers, and privacy concerns may be sent to the contact above.

## 8. Changes to this policy

This policy may be updated if Evil Bot's functionality or data practices change. The effective date above will be revised when changes are made. Material changes will be communicated through an appropriate available channel.

## 9. Contact

For questions, privacy requests, or reports of misuse, contact: **<me@mehdijai.com>**.

---
layout: ../layouts/md.astro
title: Rebuild Anisé - Privacy Policy
---

<br><br>

# Privacy Policy

*Last updated: June 12, 2026*

## I. Introduction

This page outlines the information collected and stored by Rebuild Anisé (the "Bot"). Moreover, this page should explain how it is used, your rights regarding that data, and how it is collected. By using the Bot, you agree to the collection and use of this information as described in this policy.

The Bot is not intended for use by individuals under the age of 13. By using the Bot, you confirm that you are at least 13 years of age. If you are under 13, please discontinue use immediately.

This website does not use cookies or any form of web tracking.

## II. Data the Bot collects

To provide its Services, the Bot may collect and store certain information, including but not limited to:

- **Discord User IDs**
    - Commands in the "BlablaLink" category use the user's Discord User ID in order to identify which BlablaLink account is associated with this user.
    - Commands in the "Gacha" category use the user's Discord User ID to track results from the `/gacha` and `/mold` commands. Such results can be seen when using the `/inventory` command.
- **Discord Server IDs**
    - Commands in the "AI Chatbot" category use the server's Discord Server ID in order to identify what Webhook URL is provided by a server administrator, if the server has linked a Webhook through `/ai privaty`.
    - The AI chatbot feature uses the server's Discord Server ID to verify which channels are whitelisted for AI interactions.
    - The Bot also uses the server's Discord Server ID to verify which channels are whitelisted for Datamine commands.
- **Discord Channel IDs**
    - Channel IDs are stored when a channel is whitelisted for Datamine commands by the bot developer.
    - Channel IDs are stored when a channel is whitelisted for AI chatbot interactions.
    - Some commands may also access the Discord Channel ID of the channel a message was sent in at runtime for processing purposes. This data is not stored unless explicitly stated above.
- **Discord Webhooks**
    - The Webhook URL of a server is stored when a server administrator links it through `/ai privaty`.
    - The AI chatbot feature uses this information to operate Extensions, which are only available through linking a server's Webhook URL through `/ai privaty`.
- **BlablaLink IDs**
    - This information is stored when a user links their BlablaLink ID through `/bla-link`.
    - This information can be removed when a user uses `/bla-unlink` (if the user has a linked BlablaLink account).
    - This information is used when a user uses a command from the "BlablaLink" category with the `id` and `username` arguments unfilled.
- **Message Content**
    - Message content is read to process prefix-based commands (`anis,`, `anise,`, `anisé,`, `s;`) and AI chatbot interactions, including Extensions.
    - Message content is processed in memory only and is never written to disk or logged.
    - For AI chatbot interactions, recent conversation history is retained in memory to provide context for ongoing interactions: up to 30 messages for Anisé and up to 15 messages for Extensions. This history is discarded when the Bot restarts and is never written to disk or logged.
    - For AI chatbot interactions, the following data is passed transiently to DeepSeek's API solely for the purpose of generating a response: username, server nickname (if set), message content, and replied message content (if applicable).

## III. Data Storage and Security

I try to take reasonable measures to protect your data from unauthorized access or misuse. However, as with any online service, I cannot guarantee absolute security.

- The following data is persistently stored: Discord User IDs (for BlablaLink and Gacha features), Discord Server IDs, Discord Channel IDs (for whitelisted channels), Discord Webhook URLs, and BlablaLink IDs.
- Message content is never written to disk or logged. Conversation history for AI chatbot interactions is retained in memory only and is lost when the Bot restarts.
- Data is not shared, sold, or used for advertising purposes.
- Where third-party APIs are used, only the minimum data required for that feature is transmitted. See Section V for details.

## IV. Data Retention and Removal

Data is only kept for as long as necessary to provide the Bot's services. If you wish to have your data removed, you may request deletion by contacting me (see Section VI). I will endeavour to respond within a reasonable timeframe.

If you wish to remove your data without directly contacting me, you may use the following methods:

- **BlablaLink ID** - The BlablaLink ID associated with your Discord account can be removed through `/bla-unlink`. This removes both the Discord User ID and the BlablaLink ID in the process.
- **Gacha Statistics** - The results from `/gacha` and `/mold` associated with your account can be removed through `/inventory` by pressing the "Reset my inventory" button. This only removes the Gacha Statistics; your Discord User ID will still be stored if you continue using other features.

The following data can only be removed by contacting the bot developer directly:

- **Whitelisted Channel IDs** - Channel IDs whitelisted for Datamine commands or AI chatbot interactions are managed solely by the bot developer and cannot be self-removed.
- **Discord Server IDs** - Server IDs stored in relation to whitelisted channels or AI chatbot configuration can be removed upon request.

Conversation history retained in memory for AI chatbot interactions is not persistent and is automatically discarded when the Bot restarts. No action is required to remove it.

## V. Third-party Services

The Bot uses third-party APIs to provide certain features. Only the minimum data required for each service's functionality is transmitted. I am not responsible for how third-party services handle your data; please review their respective privacy policies.

- **DeepSeek**: Used for AI chatbot responses (Anisé and Extensions). The following information is transmitted transiently per request solely for response generation and is not stored or retained by the Bot after the conversation history limit is reached (30 messages for Anisé, 15 for Extensions). Please review DeepSeek's privacy policy for how they handle data on their end.
    - **Username**: The Discord username of the user who sent the message.
    - **Server Nickname**: The user's server nickname, if one is set.
    - **Message Content**: The content of the message that triggered the AI chatbot.
    - **Replied Message Content**: If the triggering message is a reply to another message, the content of that replied message is also included for context.
    - [DeepSeek Privacy Policy](https://www.deepseek.com/privacy)
- **BlablaLink**: Used for BlablaLink-related commands. Discord User IDs and BlablaLink IDs may be transmitted.
    - [BlablaLink Privacy Policy](https://nikke-en.com/privacypolicy/)
- **DotGG**: Used for game information lookups.
    - [DotGG Privacy Policy](https://dotgg.gg/privacy/)
- **Prydwen Institute**: Used for game information lookups.
    - [Prydwen Institute Privacy Policy](https://www.prydwen.gg/privacy-policy/)

An outline of the data source URLs the Bot uses for game information lookups can be seen by using the `/api-info` command. This does not cover all third-party services listed above.

## VI. Your Rights

As a user, you have the right to:

- Request access to the data stored about you.
- Request deletion of your data, subject to the limitations required for the Bot's functionality.
- Stop using the Bot at any time, which will halt further data collection.

For questions, concerns, or data-related requests, you may contact me through the following channels:

- **Reddit**: [`u/ANISNO1`](https://reddit.com/u/ANISNO1/)
- **Discord**: `@skuqre`

## VII. Changes to this Policy

I may update this Privacy Policy at any time. If any significant changes are made, I will try to notify users whenever and wherever possible. Continued use of the Bot after updates constitutes acceptance of the revised policy.

<br><br>

[Back](/rb-anise/) &bull; [Terms of Service](/rb-anise/tos/)

<br><br>
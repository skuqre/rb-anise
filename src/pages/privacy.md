---
layout: ../layouts/md.astro
title: Rebuild Anisé - Privacy Policy
---

# Privacy Policy

For transparency, this page includes the information Rebuild Anisé collects and describes how Rebuild Anisé processes it.
<br><br>

The term "Rebuild Anisé" (referred interchangeably as the "Bot") refers to the **Discord entity the user interacts with**. An "interaction" occurs when **a user executes a slash command from the bot**, e.g. `/gacha` or `/nikke`.
<br><br>

**By using Rebuild Anisé, you consent to the following Privacy Policy.**

## I. Information Rebuild Anisé collects

Rebuild Anisé collects the specific information:
- Discord User ID
- Discord Guild ID

Rebuild Anisé uses the specific information in order to:
- **Provide the Bot with identification from the user**: The Bot uses the user's Discord ID in order to identify the user properly and update data about the user accordingly. Such examples include:
    - `/gacha`: When this command is executed, the Bot will save statistics on whether it's a "tens" or a "singles" pull (controlled by the "single" option from the command), at the Nikkes pulled from the results. This information is saved to a database that uses the Discord user's ID as a key.
    - `/inventory`: When this command is executed, the Bot will search for the user's inventory using their Discord ID. The information is then sent and nothing else happens.
    - `/ai ban`: When this command is executed, the Bot will save the banned user's Discord ID and the executor's Discord ID. This information is appended to the Reason provided by the executor of the command, if available.
- **Provide the Bot with identification from the guild**: The Bot uses the guild's Discord ID in order to properly update data related to the Guild. Such examples include:
    - `/ai privaty`: When this command is properly executed, the Bot will save the Guild ID from the interaction including the webhook URL provided from this command.

## II. Discord Intents

Rebuild Anisé has the intent to "Read Messages" in your Discord Server. This is what Rebuild Anisé does with those messages:
- **Developer-specific commands**: Rebuild Anisé has developer specific commands that contain specific functions only available to the developer. Such examples are `/gmt`, `/u`, and many more.
- **Quick Advise Function**: This function executes when a message:
    - Is in the designated Anisé text channel. Ask a server administrator as to what channel Anisé is designated in.
    - Starts with the `/` character.
    - Such text after the `/` character and the first space character contains a valid "kebab-case" phrase/word.
- **AI Chatting**
    - Rebuild Anisé activates this function when the message has a ping to the Bot, either directly or through replying a message from the Bot.
    - If AI extensions are properly set up, Rebuild Anisé will activate this function when the message starts with a valid name of an AI Extension (e.g. @Privaty, @Noah, **case-insensitive**).
    - Rebuild Anisé connects to [Character.AI](https://character.ai/) in order for this function to work. When this function is used, messages you send are bound to Character.AI's [Terms of Service](https://beta.character.ai/tos/) and [Privacy Policy](https://beta.character.ai/tos/).

Rebuild Anisé has the intent to get "Server Members" in your Discord Server. This is what Rebuild Anisé does with that information:
- **Get Bot's Guild Information**: The Bot accesses its own Guild Information for:
    - **AI Chatting**: In order to be consistent with the server's name for the Bot, the Bot will access its own Guild information and look for its nickname set by the Guild. It will then send a message including the nickname, appended by an "is typing..." to indicate that the AI is sending a message.

## III. Data Removal

You are able to soft-wipe your data using the "Reset my inventory" feature that is available when using the `/inventory` command once. The command only sets your "singles" and "tens" values to zero, and creates an empty JSON object in place for the "inventory" statistic.

If you'd like to thoroughly remove your data from the database, you are free to contact `@skuqre` in the Discord Server.

## IV. Contact

If you have any other concerns, you are free to contact `@skuqre` in Discord, or [`u/ANISNO1`](https://new.reddit.com/u/ANISNO1/) through Reddit.

<br><br><br><br>
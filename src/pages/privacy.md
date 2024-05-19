---
layout: ../layouts/md.astro
title: Rebuild Anisé - Privacy Policy
---

# Privacy Policy

For transparency, this page includes the information Rebuild Anisé collects and describes how Rebuild Anisé processes it.
<br><br>

The term "Rebuild Anisé" (the "Bot") refers to the **Discord entity the user interacts with**. An "interaction" occurs when a user executes a slash command from the bot, e.g. `/gacha` or `/nikke`.
<br><br>

**By using Rebuild Anisé, you consent to the following Privacy Policy.**

## I. Information Rebuild Anisé collects

Rebuild Anisé collects the specific information:
- Discord User ID

Rebuild Anisé uses the specific information in order to:
- **Provide the Bot with identification from the user**: The Bot uses the user's Discord ID in order to identify the user properly and update data about the user accordingly. Such examples include:
    - `/gacha`: When this command is executed, the Bot will save statistics on whether it's a "tens" or a "singles" pull (controlled by the "single" option from the command), at the Nikkes pulled from the results. This information is saved to a database that uses the Discord user's ID as a key.
    - `/inventory`: When this command is executed, the Bot will search for the user's inventory using their Discord ID. The information is then sent and nothing else happens.

## II. Discord Intents

Rebuild Anisé has the intent to "Read Messages" in your Discord Server. This is what Rebuild Anisé does with those messages:
- **Developer-specific commands**: Rebuild Anisé has developer specific commands that contain specific functions only available to the developer. Such examples are `/gmt`, `/u`, and many more.
- **Quick Advise function**: Rebuild Anisé activates this function when the message:
    - Is in the [`#anisé-bot-intel`](https://discord.com/channels/968096627002851379/1056120875612651570/) text channel.
    - Starts with the `/` character.
    - Such text after the `/` character and the first space character contains a valid "kebab-case" phrase/word.
- **AI chatting**: Rebuild Anisé activates this function when the message has a ping to the Bot, either directly or through replying a message from the Bot. Rebuild Anisé connects to [Character.AI](https://character.ai/) in order for this function to work. When this function is used, messages you send are bound to Character.AI's [Terms of Service](https://beta.character.ai/tos/) and [Privacy Policy](https://beta.character.ai/tos/).

## III. Data Removal

You are able to soft-wipe your data using the "Reset my inventory" feature that is available when using the `/inventory` command once. The command only sets your "singles" and "tens" values to zero, and creates an empty JSON object in place for the "inventory" statistic.

If you'd like to thoroughly remove your data (mainly Discord ID) from the database, you are free to contact `@skuqre` in the Discord Server.

## IV. Contact

If you have any other concerns, you are free to contact `@skuqre` in Discord, or [`u/ANISNO1`](https://new.reddit.com/u/ANISNO1/) through Reddit.

<br><br><br><br>
---
layout: ../layouts/md.astro
title: Rebuild Anisé - Permissions
---

## Anisé is Missing Permissions!
For Anisé to somewhat work in your server, she's gonna need some permissions.
No, **you can't just toggle "Administrator" and walk off**. *That's a bad habit*.

### Here are some of Anisé's needed permissions:
- **Add Reactions** - Anisé has some functions that add reactions to messages as feedback.
- **Attach Files** - Anisé can create images for some commands, functions, and must attach them to the messages.
- **Embed Links** - Anisé's main ways of showing items is through Discord's Legacy Embed system and Discord's "Components V2" system.
- **Read Message History** - Core functions
- **Send Messages** - Core functions
- **Send Messages in Threads** - Core functions
- **Use External Emojis** - Anisé uses a lot of custom emoji for commands. Try doing `/nikke nikke:anis` to see an example of how this is used.
- **Use External Stickers** - For future compatibility.
- **View Channels** - You are free to block Anisé from accessing certain channels, at the cost of not being able to interact with her normally.

### For server members, they may need the following permissions to interact with Anisé:
- **Use Application Commands**
  - Anisé uses slash commands as its main system of interaction. Text commands like `a!nikke` do not exist within Anisé.

Anisé does not need "Use External Apps" as those are for **user-installed** Discord applications (e.g. esmBot), Anisé is a **guild-installed** application.
Anisé does not need high-level permissions like "Ban Members" or "Kick Members" as she does not have features made for those permissions. **Anisé is a NIKKE-oriented Discord Bot**.

If you're wondering why Anisé has some intents that are enabled, here are their functions:
- **Presence** - Only to track the developer's status for AI toggles.
- **Server Members** - Some commands fetch server member profiles for core functions.
- **Message Content** - Commands that start with `anis,` and developer commands.
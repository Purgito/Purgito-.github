# Purgito

### A bot that mimics your community.

Purgito learns how your server writes and uses that knowledge to generate messages that feel like they came from the community itself.

No generic chatbot personality.
No predefined character.

**It learns from you.**

[Invite Purgito](https://discord.com/oauth2/authorize?client_id=1471724794411089920) · [Documentation](https://purgito.app/es/documentacion/) · [Support Server](https://discord.gg/5U7HKyxnBv) · [Source Code](https://github.com/Purgito/purgito-bot)

---

## What Purgito does

Purgito is built around one idea: **your community should shape the way the bot behaves.**

Once configured, it can learn from enabled channels and use that knowledge across several features.

### 💬 Community-aware chat

Purgito learns from your server's messages and can generate new ones based on how your community writes.

It can also attempt to imitate the writing style of a specific member.

### 🧠 Local learning

The core generation system is based on local Markov chains trained from server messages.

That means the bot does not rely on a giant predefined personality. Its output is shaped by the conversations it learns from.

### 🎭 Memes

Purgito can combine server images with the language it has learned to generate memes and captions.

The meme system can use local generation and, when configured by the operator, an external Groq model for caption generation.

### 🖼️ GIF collection

Servers can build their own GIF collection and use it as part of Purgito's ecosystem.

### ▶️ YouTube notifications

Purgito can monitor configured YouTube channels and notify a Discord channel when new videos are published.

### ⚙️ Server configuration

Advanced configuration is available through Purgito's web dashboard, including settings for chat behavior, triggers, embeds, templates and other server-level options.

---

## Built for communities, not just servers

Purgito keeps its data scoped to the Discord server where it was learned.

Learning data, configuration and server features are designed around individual communities rather than a single global model shared between every server.

NSFW channels are excluded from learning entirely.

For the full details, see the [Privacy Policy](https://purgito.app/es/privacidad/).

---

## Open source

Purgito is open source and distributed under the **MIT License**.

The project contains the bot itself, its web/API layer, generation systems, storage integration, deployment configuration and automated tests.

```text
src/
├── cogs/           Discord bot features
├── generation.py   Text generation
├── markov_engine.py
├── meme_generator.py
├── webapi.py       Web/API layer
├── r2.py           Persistent media storage
└── tests/          Automated test suite
```

See the [repository](https://github.com/Purgito/purgito-bot) for the complete source tree.

---

## Documentation

The project includes technical documentation covering:

* Architecture
* API
* Discord integration
* Development
* Generation
* Infrastructure
* Security
* Storage
* Reference

→ [Read the documentation](https://purgito.app/es/documentacion/)

---

## Contributing

Bug reports, ideas and contributions are welcome.

The repository includes issue templates, pull request guidelines, automated CI and dependency monitoring.

Before contributing, read [CONTRIBUTING.md](https://github.com/Purgito/purgito-bot/blob/main/CONTRIBUTING.md).

For security-sensitive reports, see [SECURITY.md](https://github.com/Purgito/purgito-bot/blob/main/SECURITY.md).

---

## Links

|                   |                                                                              |
| ----------------- | ---------------------------------------------------------------------------- |
| 🌐 Website        | https://purgito.app                                                          |
| 🤖 Invite Purgito | [Invite](https://discord.com/oauth2/authorize?client_id=1471724794411089920) |
| 💬 Community      | [Discord](https://discord.gg/5U7HKyxnBv)                                     |
| 📚 Documentation  | [purgito.app/es/documentacion](https://purgito.app/es/documentacion/)        |
| 💻 Source         | [github.com/Purgito/purgito-bot](https://github.com/Purgito/purgito-bot)     |

---

<p align="center">
  <sub>Built for communities that have their own way of speaking.</sub>
</p>
# 🧠 murmapp.core

```bash
╭─────────────────────────────────────────────╮
│    murmapp.core: logic & routing layer      │
│     for secure, anonymized message flow     │
╰─────────────────────────────────────────────╯
````

`murmapp.core` is the central orchestration service in the Murmapp ecosystem. It connects anonymized user events with domain-specific logic and routes messages between trusted boundary services (`hook`, `caster`, etc.).

---

## 🚧 Status

This service is currently under active development.
Expect frequent changes, new message formats, and updated processing pipelines.

---

## 🔗 Part of the Murmapp Ecosystem

| Project                                                           | Description                                                       |
| ----------------------------------------------------------------- | ----------------------------------------------------------------- |
| [`murmapp.hook`](https://github.com/eugene-ruby/murmapp.hook)     | Secure Telegram webhook receiver with ID redaction and encryption |
| [`murmapp.caster`](https://github.com/eugene-ruby/murmapp.caster) | Trusted dispatcher for decrypted message delivery to Telegram API |
| [`murmapp.docs`](https://github.com/eugene-ruby/murmapp.docs)     | Full documentation and whitepapers                                |

---

## 📝 License

This project is licensed under the [MIT License](/LICENSE).


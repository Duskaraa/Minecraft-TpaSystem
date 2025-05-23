# TPASystem Addon for Minecraft Bedrock

📦 **TPASystem** is a Minecraft Bedrock Edition addon that allows players to send teleportation requests (`/tpa`), accept (`/tpaccept`), or deny (`/tpdeny`) requests in a secure and permission-based system.

---

## ✨ Features

- 🔁 `/tpa <player>` - Send a teleport request.
- ✅ `/tpaccept` - Accept a teleport request.
- ❌ `/tpdeny` - Deny a teleport request.
- ⏳ Auto-expiring requests (30s default).
- 🔒 Optional permission system to restrict usage.
- 💬 Custom messages and sound feedback.

---

## 🧱 Installation

1. Clone or download this repo.
2. Move the contents of `behavior_packs/` and `resource_packs/` into your Minecraft world folder.
3. Enable both packs in your world settings.
4. Make sure experimental scripting features are enabled.

---

## 💻 Commands

| Command        | Description                  |
|----------------|------------------------------|
| `/tpa <player>` | Sends a teleport request.     |
| `/tpaccept`     | Accepts the last TPA request. |
| `/tpdeny`       | Denies the last TPA request.  |

---

## 🛠 Configuration

Modify the `main.js` file to:
- Change timeout duration
- Customize messages
- Hook into your permission system

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

PRs and feedback are welcome! Submit a pull request or open an issue to contribute.

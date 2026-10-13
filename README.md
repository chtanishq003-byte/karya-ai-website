# karya-ai-website
AI 
             # 🤖 Karya AI

### Your AI. Your Rules.

**Karya AI** is a personal AI assistant powered by Ollama and Python. It is designed to run from a portable folder on Windows, with AI chat, saved conversation history, and terminal commands.

> ⚡ **Portable • Local AI • Windows • Python • Ollama**

## ✨ Features

- 🧠 **AI Chat** — chat with your configured AI model.
- 💬 **Conversation History** — save and review previous conversations.
- 🧹 **History Management** — remove selected history entries or reset history with confirmation.
- ⚡ **Portable Setup** — keep Karya's files together in one folder.
- 🔧 **Command-Based Controls** — manage your conversations directly from the terminal.

## 🚀 Getting Started

1. Open the Karya portable folder.
2. Run `Karya.bat`.
3. Wait for Karya to start.
4. Type your message and press Enter.
5. Use the commands below to manage your chats.

Karya requires its configured AI model and runtime to be available. Keep the portable folder structure intact.

## ⌨️ Commands

| Command | Description |
|---|---|
| `/chat.history` | View saved conversation history |
| `/rm 1 2 3` | Remove selected history entries by their displayed numbers |
| `/rest` | Request a history reset; confirm when prompted |
| `/new` | Start a new conversation |
| `/clear` | Clear the current view or conversation, depending on the version |
| `/exit` | Exit Karya |

**Example:**

```text
/chat.history
/rm 1 3
/rest
/new
/clear
/exit
```

Use the commands supported by your current version. History numbering depends on the list displayed by Karya.

## 📁 Portable Folder Structure

```text
KaryaPortable/
├── App/
│   └── karya.py
├── Ollama/
│   └── ollama.exe
├── Models/
│   └── Ollama/
└── Karya.bat
```

Your exact folder contents may vary by version. Keep required files in their expected locations so the launcher can find them.

## 🔒 Privacy

Karya is designed to use a local AI model through Ollama. Local processing can help keep conversations on your computer, but network-connected features may communicate with external services. Avoid entering passwords, API keys, or other sensitive information.

## 🛠️ Troubleshooting

**Karya does not start**
- Check that the portable folder structure is intact.
- Make sure Python is available if your version depends on an installed Python runtime.
- Read any error messages shown in the terminal.

**The AI does not respond**
- Check that Ollama is running.
- Verify that the configured model is available.
- Confirm that Karya and Ollama use the same host and port.

**History commands fail**
- Use `/chat.history` to check the current history numbering.
- Make sure the history file is readable and is not corrupted.

## 🗺️ Future Plans

- [ ] More built-in commands
- [ ] Improved conversation management
- [ ] Better error handling
- [ ] A graphical user interface
- [ ] More customization options

## 🤝 Contributing

Suggestions, bug reports, and ideas for new commands are welcome. Please include the steps to reproduce any reported issue.

## 📜 License

A license has not yet been specified. Add a license file if you intend to grant others permission to reuse, modify, or distribute Karya.

---

**Built with curiosity. Made to keep growing.**

*Karya AI — Your AI. Your Rules.*

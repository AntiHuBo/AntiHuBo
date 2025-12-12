# AntiHuBo (AI Control Tower)

> Stop being the bottleneck when using multiple AI tools simultaneously

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## 🤔 The Problem

As AI tools evolve, paradoxically, **humans become the bottleneck**.

```
Running code generation in Claude Code...
Writing docs in ChatGPT...
Waiting for refactoring in Cursor...

"Which one responded?"
"What was I doing again?"
"What should I check first?"
```

When using multiple AI tools simultaneously:
- 🔄 Context switching overhead increases
- 🧠 Cognitive load skyrockets
- ⏰ Time wasted checking "Did it respond yet?"

## 💡 The Solution

**AntiHuBo** is a desktop app that shows the status of all your AI tools at a glance.

### Key Features

- **📊 Unified Dashboard**: See all AI tool statuses in one screen
- **🔔 Smart Notifications**: Get notified when responses complete or errors occur
- **📝 Context Reminder**: See "what you were doing" when switching back to a tool
- **🔗 Related Tasks**: Link similar tasks across different tools

### Supported AI Tools

| Tool | Status | Monitoring Method |
|------|--------|-------------------|
| Claude Code | ✅ Supported | Process + Logs |
| ChatGPT | ✅ Supported | Browser Extension |
| Cursor | ✅ Supported | Manual + Vision |
| Perplexity | 🚧 Planned | Contributions welcome! |

## 🚀 Installation

### Requirements

- Node.js 18+
- Chrome (for ChatGPT monitoring)
- Claude API Key (for Vision fallback)

### Setup

```bash
git clone https://github.com/[your-username]/antihubo.git
cd antihubo
npm install
npm run dev
```

### Chrome Extension Setup

1. Open `chrome://extensions` in Chrome
2. Enable "Developer mode"
3. Click "Load unpacked" → Select the `extension/` folder

## 🏗️ Architecture

See [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md) for details.

## 🛣️ Roadmap

See [docs/ROADMAP.md](docs/ROADMAP.md) for details.

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first.

### Good First Issues

- [ ] Add Perplexity integration
- [ ] Dark mode support
- [ ] i18n (Korean/English)
- [ ] Windows testing & bug fixes

## 📄 License

[Apache License 2.0](LICENSE)

## 🙏 Acknowledgments

- [Electron](https://www.electronjs.org/)
- [Anthropic Claude API](https://www.anthropic.com/)
- All contributors!

---

**AntiHuBo** - Don't let humans be the bottleneck in the AI era 🚀



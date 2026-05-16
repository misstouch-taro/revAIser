# revAIser

**AI-powered text proofreading for Windows.**
Bring your own API key from Groq (free), OpenAI, or Anthropic Claude — paste text, press Ctrl+Enter, accept the AI's suggestions hunk-by-hunk in a side-by-side diff view.

![Windows](https://img.shields.io/badge/Windows-10%2F11-blue?logo=windows)
![License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-1.0.0-purple)

---

## Why revAIser?

- **Your text never leaves your machine without your key.** No telemetry. No analytics. No developer-side account.
- **Per-hunk accept/reject.** WinMerge-style diff with Alt+↑/↓ to navigate, Alt+← to apply.
- **Switchable providers.** Groq (free), OpenAI, Anthropic — pick whichever fits your wallet and latency needs.
- **Bilingual UI.** English / 日本語. Tray icon, installer, and menu all localized.
- **Dark mode** follows your OS theme.

---

## Install

### Microsoft Store (recommended, coming soon)
🚧 *Awaiting certification — see [Releases](https://github.com/misstouch-taro/revAIser/releases) for an installer in the meantime.*

### Direct download (GitHub Releases)
Grab the latest `revAIser-Windows-1.0.0-Setup.exe` from the **[Releases](https://github.com/misstouch-taro/revAIser/releases)** page.

The installer is unsigned at the moment, so Windows SmartScreen may warn you the first time. Click **More info → Run anyway**. (Once the Store listing is live, those builds will be Microsoft-signed.)

---

## Quick start

1. Launch revAIser. The app starts in English; switch to 日本語 from the gear ⚙ → *Language* if you prefer.
2. Click ⚙ → paste your API key for **Groq** (free; sign up at https://console.groq.com), **OpenAI** (https://platform.openai.com), or **Anthropic** (https://console.anthropic.com).
3. Drag any `.txt` / `.md` / `.csv` / `.log` file onto the window, or `Ctrl+O` to open.
4. Press **Ctrl+Enter** ("Check"). AI suggestions appear in the right pane.
5. **Alt+↓** to step through hunks, **Alt+←** to accept, **Ctrl+Shift+A** to accept all.
6. **Ctrl+S** to save.

Right-click the desktop and pick **「クリップボードを校正」 / "Proofread clipboard"** to run revAIser on whatever text is currently on the clipboard.

---

## Keyboard shortcuts

| Key | Action |
|-----|--------|
| Ctrl+O | Open file |
| Ctrl+S | Save |
| Ctrl+W | Close file |
| Ctrl+Enter | Run AI check |
| Alt+↑ / Alt+↓ | Previous / next hunk |
| Alt+← | Apply current hunk |
| Ctrl+Shift+A | Apply all hunks |
| Ctrl+Z | Undo |
| Ctrl+Shift+Y *(global)* | Launch with clipboard contents |
| Ctrl + 🖱 | Font size up / down |

---

## Privacy

revAIser does **not** collect, transmit, or store any personal data on the developer's servers. Text and API keys you enter are sent only to the AI provider you have configured, governed by that provider's privacy policy. See [PRIVACY.md](PRIVACY.md) for details.

---

## Support

- **Bug reports / feature requests**: open an issue at https://github.com/misstouch-taro/revAIser/issues
- **Microsoft Store reviews**: once the Store listing is live

---

## License

MIT. See [LICENSE](LICENSE).

---

**Author**: [misstouch-taro](https://github.com/misstouch-taro)

> revAIser source code is maintained in a private repository. This public repo hosts the distribution, documentation, and issue tracker.

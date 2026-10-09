# pitchside

pitchside coaches you live during sales calls. It transcribes both sides of the call on your
computer, and when the customer asks a question or raises an objection, it suggests what to say,
using only your own materials: product sheet, pricing, competitors and objection notes. Every
conversation is saved by customer, and you can browse it by day, month and year and export it to
your CRM.

This repository holds pitchside's installers and update files only.

## Download

Get the latest version from **[Releases](https://github.com/hamiltonjose/pitchside-release/releases/latest)**:

| System | File |
|---|---|
| Windows 10 or 11 (64-bit) | `pitchside-<version>-setup.exe` |
| macOS 14.2 or later, Apple Silicon (M1 or newer) | `pitchside-<version>-arm64.dmg` |

Once installed, pitchside updates itself from this page.

### Beta notes

- **Windows:** beta installers aren't code-signed yet, so Windows may show "Windows protected your
  PC". Choose **More info → Run anyway**.
- **First run:** pitchside downloads its speech model, about 650 MB, once.
- **Permissions:** pitchside asks for the microphone, to hear your side. On macOS it also asks for
  System Audio Recording, to hear the other side.

## Privacy

- Speech is transcribed on your computer. Audio never leaves it and isn't saved.
- Suggestions use only your own materials and what was said on the call.
- When you ask for a suggestion or a summary, the text goes to the AI provider you chose (Claude,
  OpenAI, Gemini or Grok). With a local model (Ollama), everything stays on your computer.
- Transcription laws differ by country and state, and some require everyone's consent. pitchside
  shows an announcement for you to read at the start of every call. Following the law is your
  responsibility.

## Licence

© 2026 Atolus Intelligence. All rights reserved. pitchside is proprietary software. The
open-source components it includes are listed, with their licences, in the app under
**Settings → About → Third-party licences**.

[atolus.com](https://www.atolus.com)

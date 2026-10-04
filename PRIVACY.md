# Privacy

spitr has no account, no analytics and no telemetry. It does not send anything to the developer.
This page lists every way data leaves your computer when you use it, and what stays local.

Provider of spitr: DevSpace Douglas, Elias Douglas, Bruchstrasse 48, 6003 Luzern, Switzerland,
hello@eliasdouglas.ch.

## What stays on your computer

- **Your voice.** spitr records only while you hold the dictation key (or between start and stop
  in hands-free mode). The audio is transcribed on your computer by the speech model and then
  discarded. It is never written to disk and never sent anywhere.
- **The app you dictate into.** To pick a writing style, spitr reads the name of the active app and
  its window title. They are used on your computer only and are not sent with the text.
- **Your clipboard.** To paste the text, spitr puts it on the clipboard for a moment and then
  restores what was there before.
- **Your settings and API keys**, stored as plain text in `~/.config/spitr/config.json` (macOS) or
  `%APPDATA%\spitr\config.json` (Windows). Anyone with access to your user account can read them;
  protect your account accordingly.

## What leaves your computer

| When | What is sent | To whom |
| --- | --- | --- |
| You set up AI cleanup with your own key | The transcript of each dictation, your style rules and the name of the matching style profile | The provider you chose (e.g. Anthropic, OpenAI, Groq, OpenRouter). With Ollama or another local endpoint, nothing leaves your computer. Without a key, nothing is sent. |
| You set an ElevenLabs key for read-aloud | The text you selected to be read aloud | ElevenLabs. Without that key, read-aloud uses your system voice on your computer. |
| First launch on macOS | A download request for the speech model | Hugging Face (huggingface.co) |
| You install the model on Windows | A download request for the speech model | GitHub (github.com) |
| Once a day on macOS, and when you install an update | A request for the update feed `appcast.xml` (and the update itself), which shows GitHub your IP address and app version | GitHub (raw.githubusercontent.com, github.com) |

The cleanup and read-aloud providers process your text under their own terms and privacy policies,
under your own account with them, and may charge you for it. spitr has no influence on what they
do with it. Check their terms before you dictate anything confidential, personal data of others, or
data you are bound to keep secret.

## Recording other people

spitr is meant for your own voice. Recording other people's words without their consent can be
unlawful (in Switzerland, for example, under Art. 179bis of the Criminal Code). You are responsible
for how you use it.

## Questions

Write to hello@eliasdouglas.ch.

*Last updated: 4 October 2026.*

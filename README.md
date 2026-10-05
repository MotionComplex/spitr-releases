# spitr

Hold a key, talk, and your words appear at the cursor in any app. spitr transcribes your voice
on your own computer with NVIDIA Parakeet v3, optionally lets a language model of your choice
remove the fillers and fix the punctuation, and types the result where you are writing. Select text
and press a shortcut to hear it read aloud.

This repository hosts the builds and the update feed. The source code is private.

## Download

| | Requirements | Get it |
| --- | --- | --- |
| **macOS** | macOS 14 or later, Apple silicon (M1 or newer) | `spitr-<version>.dmg` from the [latest release](https://github.com/MotionComplex/spitr-releases/releases/latest) |
| **Windows** (pre-release) | 64-bit Windows 10 (2004 or later) or Windows 11 | `spitr-Setup.exe` from the newest *spitr for Windows* entry on the [releases page](https://github.com/MotionComplex/spitr-releases/releases) |

Both are free.

## Install

Step by step, with a picture of every dialog:

- **[Install on macOS](docs/install-macos.md):** allow the first launch, then grant Microphone and
  Accessibility.
- **[Install on Windows](docs/install-windows.md):** run Setup and get past SmartScreen, the speech
  model downloads itself, allow the microphone.

## Quick start

| | macOS | Windows |
| --- | --- | --- |
| Dictate | Hold **right ⌥ Option**, talk, release | Hold **right Ctrl**, talk, release |
| Cancel while recording | **Esc** | **Esc** |
| Read selected text aloud | **⌃⌥S** | **Ctrl+Alt+S** |
| Settings, style, permissions check | Menu bar icon | Tray icon |
| Updates | Checked daily, offered to install; or menu bar icon → **Check for Updates…** | Downloaded in the background, applied on the next restart; or tray icon → **Check for Updates…** |

## Privacy in one paragraph

Your voice never leaves your computer: it is transcribed locally and discarded. spitr has no
account, no analytics and no telemetry. Text is only sent somewhere if you connect a cleanup
provider or ElevenLabs with your own key, and then only to that provider. Details:
[PRIVACY.md](PRIVACY.md).

## Legal

spitr is provided free of charge and **as is, without warranty**, by DevSpace Douglas, Elias
Douglas, Lucerne, Switzerland. Use is subject to the [terms of use](TERMS.md). Third-party
components and the speech model keep their own licences:
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Contact: hello@eliasdouglas.ch · [eliasdouglas.ch](https://www.eliasdouglas.ch)

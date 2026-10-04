# Third-party notices

spitr uses the following components and models. Each remains under its own licence; the full
licence texts are at the linked sources.

## Speech model

**NVIDIA Parakeet TDT 0.6B v3**, by NVIDIA, licensed under
[Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
Source: [huggingface.co/nvidia/parakeet-tdt-0.6b-v3](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3).

spitr uses converted versions of this model, which are also CC BY 4.0:

- macOS: the CoreML conversion by FluidInference,
  [huggingface.co/FluidInference/parakeet-tdt-0.6b-v3-coreml](https://huggingface.co/FluidInference/parakeet-tdt-0.6b-v3-coreml).
- Windows: the sherpa-onnx export by the k2-fsa project,
  `sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8`,
  [github.com/k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx/releases/tag/asr-models).

The model is downloaded from these sources, not distributed in this repository. spitr does not
modify it.

## Software

| Component | Used in | Licence | Source |
| --- | --- | --- | --- |
| FluidAudio | macOS | Apache License 2.0 | [github.com/FluidInference/FluidAudio](https://github.com/FluidInference/FluidAudio) |
| Sparkle | macOS | MIT-style licence (Sparkle `LICENSE`) | [github.com/sparkle-project/Sparkle](https://github.com/sparkle-project/Sparkle) |
| sherpa-onnx (`org.k2fsa.sherpa.onnx`) | Windows | Apache License 2.0 | [github.com/k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) |
| NAudio | Windows | MIT | [github.com/naudio/NAudio](https://github.com/naudio/NAudio) |
| System.Speech | Windows | MIT | [github.com/dotnet/runtime](https://github.com/dotnet/runtime) |
| .NET runtime (bundled) | Windows | MIT | [github.com/dotnet/runtime](https://github.com/dotnet/runtime) |

## Fonts

| Font | Licence | Source |
| --- | --- | --- |
| Orbitron | SIL Open Font License 1.1 | [fonts.google.com/specimen/Orbitron](https://fonts.google.com/specimen/Orbitron) |
| Space Mono | SIL Open Font License 1.1 | [fonts.google.com/specimen/Space+Mono](https://fonts.google.com/specimen/Space+Mono) |

## Trademarks

NVIDIA, Parakeet, Apple, macOS, Microsoft, Windows, Anthropic, OpenAI, Groq, OpenRouter, Ollama and
ElevenLabs are trademarks of their respective owners. spitr is an independent project, not
affiliated with or endorsed by any of them.

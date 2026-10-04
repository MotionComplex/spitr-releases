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
- Windows: the sherpa-onnx export `sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8`, published on
  Hugging Face by csukuangfj, a maintainer of the k2-fsa project's sherpa-onnx,
  [huggingface.co/csukuangfj/sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8](https://huggingface.co/csukuangfj/sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8).

The model is downloaded from these sources, not distributed in this repository. spitr does not
modify it.

## Software

| Component | Used in | Licence | Source |
| --- | --- | --- | --- |
| FluidAudio | macOS | Apache License 2.0 | [github.com/FluidInference/FluidAudio](https://github.com/FluidInference/FluidAudio) |
| Sparkle | macOS | MIT-style licence (Sparkle `LICENSE`) | [github.com/sparkle-project/Sparkle](https://github.com/sparkle-project/Sparkle) |
| sherpa-onnx (`org.k2fsa.sherpa.onnx`) | Windows | Apache License 2.0 | [github.com/k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) |
| ONNX Runtime (`onnxruntime.dll`, shipped with sherpa-onnx) | Windows | MIT | [github.com/microsoft/onnxruntime](https://github.com/microsoft/onnxruntime) |
| Velopack | Windows | MIT | [github.com/velopack/velopack](https://github.com/velopack/velopack) |
| NAudio | Windows | MIT | [github.com/naudio/NAudio](https://github.com/naudio/NAudio) |
| System.Speech | Windows | MIT | [github.com/dotnet/runtime](https://github.com/dotnet/runtime) |
| .NET runtime (bundled) | Windows | MIT | [github.com/dotnet/runtime](https://github.com/dotnet/runtime) |

## Fonts

| Font | Licence | Source |
| --- | --- | --- |
| Orbitron | SIL Open Font License 1.1 | [fonts.google.com/specimen/Orbitron](https://fonts.google.com/specimen/Orbitron) |
| Space Mono | SIL Open Font License 1.1 | [fonts.google.com/specimen/Space+Mono](https://fonts.google.com/specimen/Space+Mono) |

The macOS app ships Orbitron unmodified. The Windows app ships three static weights derived from
it, renamed **Spitr Display** because the Open Font License reserves the name "Orbitron" for
unmodified versions; they remain under the SIL Open Font License 1.1. Both apps include the
licence texts (`OFL-Orbitron.txt`, `OFL-SpaceMono.txt`).

## Trademarks

NVIDIA, Parakeet, Apple, macOS, Microsoft, Windows, Anthropic, OpenAI, Groq, OpenRouter, Ollama and
ElevenLabs are trademarks of their respective owners. spitr is an independent project, not
affiliated with or endorsed by any of them.

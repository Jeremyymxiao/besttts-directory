# BestTTS — Speech Models & Voice AI Directory

[Website](https://besttts.org) · [Browse all models](https://besttts.org/models) · [Compare models](https://besttts.org/compare) · [中文介绍](README.zh-CN.md)

**BestTTS helps developers, creators, and researchers discover and compare text-to-speech models, commercial speech APIs, and open-source voice tools.** Each product page brings together its use cases, features, integration guidance, pricing information, and upstream resources. Selected pages also offer audio samples or links to official demos.

This repository is the public introduction and product index for [besttts.org](https://besttts.org). The website is built with Next.js, React, TypeScript, and Tailwind CSS, using the [ShipAny](https://shipany.ai) template, and runs on Cloudflare Workers with D1.

## Explore BestTTS

| Page                                                                                                                                           | What you can find                              |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| [Home](https://besttts.org)                                                                                                                    | Featured models and recent additions           |
| [Model directory](https://besttts.org/models)                                                                                                  | All published product pages                    |
| [Model comparison](https://besttts.org/compare)                                                                                                | Speech models and APIs compared side by side   |
| [Text-to-speech category](https://besttts.org/categories/text-to-speech)                                                                       | Speech synthesis models, APIs, and local tools |
| [Speech-to-text category](https://besttts.org/categories/speech-to-text)                                                                       | Transcription models and workflows             |
| [Gemini 3.8 vs. ElevenLabs v4 vs. Cartesia Sonic 3.6](https://besttts.org/compare/gemini-3-8-flash-tts-vs-elevenlabs-v4-vs-cartesia-sonic-3-6) | A focused comparison of three speech APIs      |
| [Blog](https://besttts.org/blog)                                                                                                               | Guides to choosing and using speech models     |

## Current product pages

**25 product pages**, checked against the live directory and sitemap on **October 8, 2026**. Every BestTTS link below opens the corresponding product page. The directory also includes transcription, audio understanding, and voice-agent components; their roles are identified separately.

### Commercial text-to-speech APIs & studios

| Product                | Focus                                          | BestTTS page                                                      | Official resources                                                                                       |
| ---------------------- | ---------------------------------------------- | ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Amazon Polly           | Speech synthesis in the AWS ecosystem          | [View product](https://besttts.org/models/amazon-polly)           | [AWS](https://aws.amazon.com/polly/)                                                                     |
| Microsoft Azure TTS    | Enterprise speech synthesis and custom voices  | [View product](https://besttts.org/models/azure-tts)              | [Microsoft Azure](https://azure.microsoft.com/en-us/products/ai-services/text-to-speech)                 |
| Cartesia Sonic 3.6     | Streaming speech for interactive applications  | [View product](https://besttts.org/models/cartesia-sonic)         | [Cartesia documentation](https://docs.cartesia.ai/build-with-cartesia/tts-models/latest)                 |
| ElevenLabs             | Voice generation and voice cloning             | [View product](https://besttts.org/models/elevenlabs)             | [ElevenLabs](https://elevenlabs.io)                                                                      |
| ElevenLabs v4          | Expressive narration and dialogue              | [View product](https://besttts.org/models/elevenlabs-v4)          | [ElevenLabs v4](https://elevenlabs.io/v4)                                                                |
| Fish Audio             | Hosted speech synthesis and voice cloning      | [View product](https://besttts.org/models/fish-audio)             | [Fish Audio](https://fish.audio)                                                                         |
| Gemini 3.1 Flash TTS   | Speech generation through Gemini               | [View product](https://besttts.org/models/gemini-3-1-flash-tts)   | [Google AI Studio](https://aistudio.google.com)                                                          |
| Gemini 3.8 Flash TTS   | Voice direction and expressive speech          | [View product](https://besttts.org/models/gemini-3-8-flash-tts)   | [Google documentation](https://ai.google.dev/gemini-api/docs/models/gemini-3.8-flash-tts)                |
| Google Cloud TTS       | Cloud speech synthesis and multilingual voices | [View product](https://besttts.org/models/google-cloud-tts)       | [Google Cloud](https://cloud.google.com/text-to-speech)                                                  |
| Inworld Realtime TTS-2 | Streaming speech for voice applications        | [View product](https://besttts.org/models/inworld-realtime-tts-2) | [Inworld](https://inworld.ai/realtime-tts-2)                                                             |
| MAI-Voice-2.1          | Microsoft's expressive speech model            | [View product](https://besttts.org/models/mai-voice-2-1)          | [Microsoft documentation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/mai-voices) |
| MAI-Voice-2.1-Flash    | Microsoft's low-latency speech variant         | [View product](https://besttts.org/models/mai-voice-2-1-flash)    | [Microsoft documentation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/mai-voices) |
| Murf AI                | Voiceover creation in a visual studio          | [View product](https://besttts.org/models/murf-ai)                | [Murf AI](https://murf.ai)                                                                               |
| OpenAI TTS             | Speech generation through an API               | [View product](https://besttts.org/models/openai-tts)             | [OpenAI documentation](https://platform.openai.com/docs/guides/text-to-speech)                           |
| PlayHT                 | AI voices, voice cloning, and speech APIs      | [View product](https://besttts.org/models/playht)                 | [Archived Python SDK](https://github.com/playht/pyht)                                                    |

Fish Audio also publishes a related downloadable model project: [Fish Speech on GitHub](https://github.com/fishaudio/fish-speech) and [S2-Pro on Hugging Face](https://huggingface.co/fishaudio/s2-pro). These links describe the upstream project and checkpoint; the BestTTS page covers the hosted Fish Audio service.

PlayHT remains listed because its BestTTS product page is published. Its official Python SDK is archived, and its website could not be reached during this check.

### Open-source tools & downloadable speech models

| Product             | Focus                                                                 | BestTTS page                                            | GitHub                                                                                                                   | Hugging Face                                                               |
| ------------------- | --------------------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| Breeze TTS 2        | English/Chinese speech, voice design, and cloning; restricted weights | [View product](https://besttts.org/models/breeze-tts-2) | [breezeblue-ai/breeze-tts](https://github.com/breezeblue-ai/breeze-tts)                                                  | [BreezeBlue/Breeze-TTS-2](https://huggingface.co/BreezeBlue/Breeze-TTS-2)  |
| Coqui TTS / XTTS v2 | A TTS toolkit and multilingual voice cloning                          | [View product](https://besttts.org/models/coqui-tts)    | [coqui-ai/TTS](https://github.com/coqui-ai/TTS)                                                                          | [coqui/XTTS-v2](https://huggingface.co/coqui/XTTS-v2)                      |
| Kokoro              | Lightweight local speech synthesis                                    | [View product](https://besttts.org/models/kokoro)       | [hexgrad/kokoro](https://github.com/hexgrad/kokoro)                                                                      | [hexgrad/Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M)            |
| OmniVoice           | Multilingual speech and voice cloning                                 | [View product](https://besttts.org/models/omnivoice)    | [k2-fsa/OmniVoice](https://github.com/k2-fsa/OmniVoice)                                                                  | [k2-fsa/OmniVoice](https://huggingface.co/k2-fsa/OmniVoice)                |
| Paradee             | A compact English model for local CPU inference                       | [View product](https://besttts.org/models/paradee)      | [sahilmahendrakar/paradee](https://github.com/sahilmahendrakar/paradee)                                                  | [Paradee-8M-v1.0](https://huggingface.co/sahilmahendrakar/Paradee-8M-v1.0) |
| Piper               | Local and offline speech synthesis                                    | [View product](https://besttts.org/models/piper)        | [Current development](https://github.com/OHF-Voice/piper1-gpl) · [Original repository](https://github.com/rhasspy/piper) | [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices)        |
| VoxCPM2             | Multilingual voice cloning and voice design                           | [View product](https://besttts.org/models/voxcpm2)      | [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)                                                                      | [openbmb/VoxCPM2](https://huggingface.co/openbmb/VoxCPM2)                  |

Code and model weights may have different licenses. Breeze TTS 2's [model card](https://huggingface.co/BreezeBlue/Breeze-TTS-2) restricts self-hosted weights and outputs to research and non-commercial use; XTTS v2 uses the [Coqui Public Model License](https://huggingface.co/coqui/XTTS-v2). Piper's [original repository](https://github.com/rhasspy/piper) points to the current development repository above. Individual Piper voices have their own model cards and terms.

### Transcription, audio understanding & voice-agent models

| Product               | Role                                                                     | BestTTS page                                                     | Official resources                                                                                                                              |
| --------------------- | ------------------------------------------------------------------------ | ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| FireRedAudio          | Audio understanding, transcription, speech synthesis, and speech editing | [View product](https://besttts.org/models/fireredaudio)          | [GitHub](https://github.com/FireRedTeam/FireRedAudio) · [Hugging Face](https://huggingface.co/FireRedTeam/FireRedAudio)                         |
| Gemini 3.5 Transcribe | Speech-to-text and live transcription                                    | [View product](https://besttts.org/models/gemini-3-5-transcribe) | [Google documentation](https://ai.google.dev/gemini-api/docs/models/gemini-3.5-transcribe)                                                      |
| PhoneLLM              | Text dialogue and tool-use core for phone voice agents                   | [View product](https://besttts.org/models/phonellm)              | [Hugging Face: Alpha 1](https://huggingface.co/pipecat-ai/phonellm-alpha-1) · [NVFP4](https://huggingface.co/pipecat-ai/phonellm-alpha-1-nvfp4) |

PhoneLLM works alongside ASR, TTS, telephony, and orchestration components. Its role is the dialogue layer in a voice-agent system.

## Contribute

Suggestions, corrections, and broken-link reports are welcome through [GitHub Issues](https://github.com/Jeremyymxiao/besttts-directory/issues) or pull requests.

- Include the corresponding BestTTS product URL and official upstream sources.
- Distinguish source code, model weights, demos, and hosted APIs when proposing links.
- Keep the English and Chinese product lists in sync.
- When adding or removing a published page, update the page count and verification date.

The website contains the full reviews and integration guides. This repository provides their public index; linked models, code, and weights remain governed by their respective upstream licenses.

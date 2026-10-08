# BestTTS — 语音模型与 Voice AI 产品目录

[访问网站](https://besttts.org) · [浏览全部模型](https://besttts.org/models) · [模型对比](https://besttts.org/compare) · [English](README.md)

**BestTTS 帮助开发者、内容创作者和研究人员发现、了解并对比文本转语音模型、商业语音 API 及开源语音工具。** 每个产品页面整理了应用场景、功能、接入方式、定价信息和官方资源；部分页面还提供音频示例或官方演示入口。

本仓库是 [besttts.org](https://besttts.org) 的公开项目介绍与产品索引。网站使用 Next.js、React、TypeScript、Tailwind CSS 和 [ShipAny](https://shipany.ai) 模板构建，部署在 Cloudflare Workers，使用 D1 数据库。

## 网站入口

| 页面                                                                                                                                            | 内容                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| [首页](https://besttts.org)                                                                                                                     | 精选模型与近期新增产品        |
| [模型目录](https://besttts.org/models)                                                                                                          | 全部已发布的产品页面          |
| [模型对比](https://besttts.org/compare)                                                                                                         | 并排查看语音模型与 API 的差异 |
| [文本转语音分类](https://besttts.org/categories/text-to-speech)                                                                                 | 语音合成模型、API 和本地工具  |
| [语音转文字分类](https://besttts.org/categories/speech-to-text)                                                                                 | 转录模型与使用流程            |
| [Gemini 3.8、ElevenLabs v4 与 Cartesia Sonic 3.6 对比](https://besttts.org/compare/gemini-3-8-flash-tts-vs-elevenlabs-v4-vs-cartesia-sonic-3-6) | 三个语音 API 的专题对比       |
| [博客](https://besttts.org/blog)                                                                                                                | 语音模型选型和使用指南        |

## 当前产品页面

截至 **2026 年 10 月 8 日**，已根据线上目录和 sitemap 核对 **25 个产品页面**。下表中的 BestTTS 链接均指向对应产品详情页。网站还收录了语音转文字、音频理解和语音代理组件，下文分别标明它们的用途。

### 商业文本转语音 API 与创作工具

| 产品                   | 主要用途                    | BestTTS 页面                                                  | 官方资源                                                                                        |
| ---------------------- | --------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Amazon Polly           | AWS 生态中的语音合成服务    | [产品详情](https://besttts.org/models/amazon-polly)           | [AWS](https://aws.amazon.com/polly/)                                                            |
| Microsoft Azure TTS    | 企业语音合成与自定义声音    | [产品详情](https://besttts.org/models/azure-tts)              | [Microsoft Azure](https://azure.microsoft.com/en-us/products/ai-services/text-to-speech)        |
| Cartesia Sonic 3.6     | 面向交互应用的流式语音      | [产品详情](https://besttts.org/models/cartesia-sonic)         | [Cartesia 文档](https://docs.cartesia.ai/build-with-cartesia/tts-models/latest)                 |
| ElevenLabs             | 声音生成与声音克隆          | [产品详情](https://besttts.org/models/elevenlabs)             | [ElevenLabs](https://elevenlabs.io)                                                             |
| ElevenLabs v4          | 富有表现力的旁白与对话      | [产品详情](https://besttts.org/models/elevenlabs-v4)          | [ElevenLabs v4](https://elevenlabs.io/v4)                                                       |
| Fish Audio             | 托管语音合成与声音克隆      | [产品详情](https://besttts.org/models/fish-audio)             | [Fish Audio](https://fish.audio)                                                                |
| Gemini 3.1 Flash TTS   | 通过 Gemini 生成语音        | [产品详情](https://besttts.org/models/gemini-3-1-flash-tts)   | [Google AI Studio](https://aistudio.google.com)                                                 |
| Gemini 3.8 Flash TTS   | 声音引导与表现力控制        | [产品详情](https://besttts.org/models/gemini-3-8-flash-tts)   | [Google 文档](https://ai.google.dev/gemini-api/docs/models/gemini-3.8-flash-tts)                |
| Google Cloud TTS       | 云端语音合成与多语言声音    | [产品详情](https://besttts.org/models/google-cloud-tts)       | [Google Cloud](https://cloud.google.com/text-to-speech)                                         |
| Inworld Realtime TTS-2 | 面向语音应用的流式语音      | [产品详情](https://besttts.org/models/inworld-realtime-tts-2) | [Inworld](https://inworld.ai/realtime-tts-2)                                                    |
| MAI-Voice-2.1          | 微软的表现力语音模型        | [产品详情](https://besttts.org/models/mai-voice-2-1)          | [Microsoft 文档](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/mai-voices) |
| MAI-Voice-2.1-Flash    | 微软的低延迟语音变体        | [产品详情](https://besttts.org/models/mai-voice-2-1-flash)    | [Microsoft 文档](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/mai-voices) |
| Murf AI                | 可视化工作室中的配音创作    | [产品详情](https://besttts.org/models/murf-ai)                | [Murf AI](https://murf.ai)                                                                      |
| OpenAI TTS             | 通过 API 生成语音           | [产品详情](https://besttts.org/models/openai-tts)             | [OpenAI 文档](https://platform.openai.com/docs/guides/text-to-speech)                           |
| PlayHT                 | AI 声音、声音克隆与语音 API | [产品详情](https://besttts.org/models/playht)                 | [已归档的 Python SDK](https://github.com/playht/pyht)                                           |

Fish Audio 还发布了相关的可下载模型项目：[Fish Speech GitHub 仓库](https://github.com/fishaudio/fish-speech) 与 [S2-Pro Hugging Face 模型页](https://huggingface.co/fishaudio/s2-pro)。这些链接对应上游项目和模型权重，BestTTS 产品页介绍的是 Fish Audio 托管服务。

PlayHT 的 BestTTS 产品页仍已发布，因此保留在列表中。它的官方 Python SDK 已归档，本次检查未能访问其官网。

### 开源工具与可下载语音模型

| 产品                | 主要用途                                 | BestTTS 页面                                        | GitHub                                                                                                 | Hugging Face                                                               |
| ------------------- | ---------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------- |
| Breeze TTS 2        | 中英语音、声音设计与克隆；权重有使用限制 | [产品详情](https://besttts.org/models/breeze-tts-2) | [breezeblue-ai/breeze-tts](https://github.com/breezeblue-ai/breeze-tts)                                | [BreezeBlue/Breeze-TTS-2](https://huggingface.co/BreezeBlue/Breeze-TTS-2)  |
| Coqui TTS / XTTS v2 | TTS 工具框架与多语言声音克隆             | [产品详情](https://besttts.org/models/coqui-tts)    | [coqui-ai/TTS](https://github.com/coqui-ai/TTS)                                                        | [coqui/XTTS-v2](https://huggingface.co/coqui/XTTS-v2)                      |
| Kokoro              | 轻量本地语音合成                         | [产品详情](https://besttts.org/models/kokoro)       | [hexgrad/kokoro](https://github.com/hexgrad/kokoro)                                                    | [hexgrad/Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M)            |
| OmniVoice           | 多语言语音与声音克隆                     | [产品详情](https://besttts.org/models/omnivoice)    | [k2-fsa/OmniVoice](https://github.com/k2-fsa/OmniVoice)                                                | [k2-fsa/OmniVoice](https://huggingface.co/k2-fsa/OmniVoice)                |
| Paradee             | 面向本地 CPU 推理的小型英语模型          | [产品详情](https://besttts.org/models/paradee)      | [sahilmahendrakar/paradee](https://github.com/sahilmahendrakar/paradee)                                | [Paradee-8M-v1.0](https://huggingface.co/sahilmahendrakar/Paradee-8M-v1.0) |
| Piper               | 本地和离线语音合成                       | [产品详情](https://besttts.org/models/piper)        | [当前开发仓库](https://github.com/OHF-Voice/piper1-gpl) · [原始仓库](https://github.com/rhasspy/piper) | [rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices)        |
| VoxCPM2             | 多语言声音克隆与声音设计                 | [产品详情](https://besttts.org/models/voxcpm2)      | [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)                                                    | [openbmb/VoxCPM2](https://huggingface.co/openbmb/VoxCPM2)                  |

代码和模型权重可能采用不同许可。Breeze TTS 2 的[模型卡](https://huggingface.co/BreezeBlue/Breeze-TTS-2)规定，自托管权重和输出仅限研究及非商业用途；XTTS v2 使用 [Coqui Public Model License](https://huggingface.co/coqui/XTTS-v2)。Piper 的[原始仓库](https://github.com/rhasspy/piper)已指向上表中的当前开发仓库，各声音权重还有各自的模型卡和使用条款。

### 转录、音频理解与语音代理模型

| 产品                  | 作用                                   | BestTTS 页面                                                 | 官方资源                                                                                                                                        |
| --------------------- | -------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| FireRedAudio          | 音频理解、转录、语音合成与语音编辑     | [产品详情](https://besttts.org/models/fireredaudio)          | [GitHub](https://github.com/FireRedTeam/FireRedAudio) · [Hugging Face](https://huggingface.co/FireRedTeam/FireRedAudio)                         |
| Gemini 3.5 Transcribe | 语音转文字与实时转录                   | [产品详情](https://besttts.org/models/gemini-3-5-transcribe) | [Google 文档](https://ai.google.dev/gemini-api/docs/models/gemini-3.5-transcribe)                                                               |
| PhoneLLM              | 电话语音代理中的文本对话与工具调用核心 | [产品详情](https://besttts.org/models/phonellm)              | [Hugging Face：Alpha 1](https://huggingface.co/pipecat-ai/phonellm-alpha-1) · [NVFP4](https://huggingface.co/pipecat-ai/phonellm-alpha-1-nvfp4) |

PhoneLLM 需要与 ASR、TTS、电话接入和编排组件配合使用，在语音代理系统中承担对话层的作用。

## 参与完善

欢迎通过 [GitHub Issues](https://github.com/Jeremyymxiao/besttts-directory/issues) 或 Pull Request 提交建议、内容更正和失效链接报告。

- 附上对应的 BestTTS 产品链接与官方上游来源。
- 添加链接时区分源代码、模型权重、演示和托管 API。
- 同步维护中英文产品列表。
- 增删已发布页面时，同时更新页面总数和核对日期。

完整的产品介绍和接入指南位于网站，本仓库提供公开索引。链接到的模型、代码和权重遵循各自上游的许可。

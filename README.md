# Awesome OpenAI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome tools, libraries, papers, and projects built using OpenAI models and APIs.

OpenAI provides state-of-the-art language models like GPT-4, Codex, and Whisper, enabling developers to build next-generation AI applications. This list aims to collect and organize high-quality resources built on top of OpenAI's technologies.

---

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Models](#models)
- [Libraries & SDKs](#libraries--sdks)
- [Developer Tools](#developer-tools)
- [Prompts & Datasets](#prompts--datasets)
- [Papers & Research](#papers--research)
- [Projects Using OpenAI](#projects-using-openai)
- [Community](#community)

---

## Official Resources

- [OpenAI Platform](https://platform.openai.com) - Official API access, documentation, and usage dashboard.
- [OpenAI Blog](https://openai.com/blog) - Product announcements, research papers, and updates.
- [OpenAI GitHub](https://github.com/openai) - Open-source tools and research by OpenAI.

## Getting Started

- [API Quickstart Guide](https://platform.openai.com/docs/quickstart)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Practical guides and code examples.
- [ChatGPT Custom GPTs](https://platform.openai.com/gpts) - Create and share your own GPTs.
- [Whisper (Speech-to-Text)](https://github.com/openai/whisper)

## Models

### Featured Models

- [GPT-4.1](https://platform.openai.com/docs/models/gpt-4.1) – Flagship GPT model for complex tasks.
- [o4-mini](https://platform.openai.com/docs/models/o4-mini) – Faster, more affordable reasoning model.
- [o3](https://platform.openai.com/docs/models/o3) – Most powerful reasoning model in the o-series.

### Reasoning Models

- [o3-mini](https://platform.openai.com/docs/models/o3-mini) – A small model alternative to o3.
- [o1](https://platform.openai.com/docs/models/o1) – Previous full o-series reasoning model.
- [o1-mini](https://platform.openai.com/docs/models/o1-mini) – A small model alternative to o1 (deprecated).
- [o1-pro](https://platform.openai.com/docs/models/o1-pro) – Version of o1 with more compute.

### Flagship Chat Models

- [GPT-4o](https://platform.openai.com/docs/models/gpt-4o) – Fast, intelligent, flexible GPT model.
- [GPT-4o Audio](https://platform.openai.com/docs/models/gpt-4o-audio-preview) – GPT-4o model capable of audio inputs and outputs.
- [ChatGPT-4o](https://platform.openai.com/docs/models/chatgpt-4o-latest) – GPT-4o model used in ChatGPT.

### Cost-Optimized Models

- [GPT-4.1 mini](https://platform.openai.com/docs/models/gpt-4.1-mini) – Balanced for intelligence, speed, and cost.
- [GPT-4.1 nano](https://platform.openai.com/docs/models/gpt-4.1-nano) – Fastest, most cost-effective GPT-4.1 model.
- [GPT-4o mini](https://platform.openai.com/docs/models/gpt-4o-mini) – Fast, affordable small model for focused tasks.
- [GPT-4o mini Audio](https://platform.openai.com/docs/models/gpt-4o-mini-audio-preview) – Smaller model capable of audio inputs and outputs.

### Realtime Models

- [GPT-4o Realtime](https://platform.openai.com/docs/models/gpt-4o-realtime-preview) – Realtime text and audio inputs and outputs.
- [GPT-4o mini Realtime](https://platform.openai.com/docs/models/gpt-4o-mini-realtime-preview) – Smaller realtime model.

### Image Generation Models

- [GPT Image 1](https://platform.openai.com/docs/models/gpt-image-1) – State-of-the-art image generation.
- [DALL·E 3](https://platform.openai.com/docs/models/dall-e-3) – Latest released version of DALL·E.
- [DALL·E 2](https://platform.openai.com/docs/models/dall-e-2) – Original image generation model.

### Text-to-Speech

- [GPT-4o mini TTS](https://platform.openai.com/docs/models/gpt-4o-mini-tts) – Text-to-speech powered by GPT-4o mini.
- [TTS-1](https://platform.openai.com/docs/models/tts-1) – Optimized for speed.
- [TTS-1 HD](https://platform.openai.com/docs/models/tts-1-hd) – Optimized for quality.

### Transcription

- [GPT-4o Transcribe](https://platform.openai.com/docs/models/gpt-4o-transcribe) – Speech-to-text powered by GPT-4o.
- [GPT-4o mini Transcribe](https://platform.openai.com/docs/models/gpt-4o-mini-transcribe) – Speech-to-text powered by GPT-4o mini.
- [Whisper](https://platform.openai.com/docs/models/whisper-1) – Open-source general-purpose speech recognition model.

### Tool-Specific Models

- [GPT-4o Search Preview](https://platform.openai.com/docs/models/gpt-4o-search-preview) – Optimized for web search.
- [GPT-4o mini Search Preview](https://platform.openai.com/docs/models/gpt-4o-mini-search-preview) – Small, fast search model.
- [computer-use-preview](https://platform.openai.com/docs/models/computer-use-preview) – Specialized for computer control.
- [codex-mini-latest](https://platform.openai.com/docs/models/codex-mini-latest) – Fast model optimized for Codex CLI.

### Embeddings

- [text-embedding-3-small](https://platform.openai.com/docs/models/text-embedding-3-small) – Small embedding model.
- [text-embedding-3-large](https://platform.openai.com/docs/models/text-embedding-3-large) – Most capable embedding model.
- [text-embedding-ada-002](https://platform.openai.com/docs/models/text-embedding-ada-002) – Legacy embedding model.

### Moderation

- [omni-moderation-latest](https://platform.openai.com/docs/models/omni-moderation-latest) – Detect harmful content in text and images.
- [text-moderation-latest](https://platform.openai.com/docs/models/text-moderation-latest) – Text-only model (deprecated).

### Older GPT Models

- [GPT-4 Turbo](https://platform.openai.com/docs/models/gpt-4-turbo) – High-performance legacy GPT-4 variant.
- [GPT-4](https://platform.openai.com/docs/models/gpt-4) – Original GPT-4 release.
- [GPT-3.5 Turbo](https://platform.openai.com/docs/models/gpt-3.5-turbo) – Cost-effective legacy GPT model.

### GPT Base Models

- [babbage-002](https://platform.openai.com/docs/models/babbage-002) – Replacement for GPT-3 ada/babbage base models.
- [davinci-002](https://platform.openai.com/docs/models/davinci-002) – Replacement for GPT-3 curie/davinci base models.

## Libraries & SDKs

- [openai-python](https://github.com/openai/openai-python) - Official Python SDK.
- [openai-node](https://github.com/openai/openai-node) - Official Node.js SDK.
- [openai-go](https://github.com/openai/openai-go) - Official Go SDK.
- [openai-ruby](https://github.com/openai/openai-ruby) - Official Ruby SDK.
- [openai-java](https://github.com/openai/openai-java) - Official Java SDK.
- [openai-dotnet](https://github.com/openai/openai-dotnet) - Official .NET SDK.
- [openai-c](https://github.com/LunaStev/openai-c) - Unofficial C SDK for OpenAI API (early-stage; chat only).
- [LangChain](https://github.com/langchain-ai/langchain) - Framework for building LLM-powered apps.
- [LlamaIndex](https://github.com/jerryjliu/llama_index) - Data framework for GPT-based applications.
- [Gradio](https://github.com/gradio-app/gradio) - UI library for building interactive ML demos.

## Developer Tools

- [Open Interpreter](https://github.com/KillianLucas/open-interpreter) - Run natural language as code.
- [Auto-GPT](https://github.com/Torantulino/Auto-GPT) - Autonomous GPT-based agent.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - Specify what you want, GPT builds it.
- [PromptLayer](https://github.com/promptlayer/promptlayer) - Prompt engineering platform with analytics.

## Prompts & Datasets

- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) - Useful and creative prompts.
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
- [OpenAI Eval Framework](https://github.com/openai/evals)

## Papers & Research

- [GPT-4 Technical Report](https://openai.com/research/gpt-4)
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)
- [Function Calling with GPT](https://openai.com/blog/function-calling-and-other-api-updates)

## Projects Using OpenAI

- [Notion AI](https://www.notion.so/product/ai)
- [GitHub Copilot](https://github.com/features/copilot)
- [ChatGPT Plugins](https://openai.com/blog/chatgpt-plugins)
- [Replit Ghostwriter](https://replit.com/site/ghostwriter)

## Community

- [OpenAI Community Forum](https://community.openai.com)
- [Discord (Unofficial)](https://discord.gg/openai)
- [r/OpenAI](https://reddit.com/r/OpenAI)

---

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

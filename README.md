# Awesome OpenAI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome tools, libraries, papers, and projects built using OpenAI models and APIs.

OpenAI provides state-of-the-art language models like GPT-4, Codex, and Whisper, enabling developers to build next-generation AI applications. This list aims to collect and organize high-quality resources built on top of OpenAI's technologies.

---

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Model](#models)
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

- [GPT-4.1](https://platform.openai.com/docs/models/gpt-4) – Flagship GPT model for complex tasks.
- [o4-mini](https://platform.openai.com/docs/models/gpt-4) – Faster, more affordable reasoning model.
- [o3](https://platform.openai.com/docs/models/gpt-4) – Most powerful reasoning model in the o-series.

### Reasoning Models

- [o3-mini](https://platform.openai.com/docs/models/gpt-4) – A small model alternative to o3.
- [o1](https://platform.openai.com/docs/models/gpt-4) – Previous full o-series reasoning model.
- [o1-mini](https://platform.openai.com/docs/models/gpt-4) – A small model alternative to o1 (deprecated).
- [o1-pro](https://platform.openai.com/docs/models/gpt-4) – Version of o1 with more compute.

### Flagship Chat Models

- [GPT-4o](https://openai.com/index/gpt-4o) – Fast, intelligent, flexible GPT model.
- [GPT-4o Audio Preview](https://openai.com/index/gpt-4o) – GPT-4o model capable of audio inputs and outputs.
- [ChatGPT-4o (latest)](https://openai.com/chat) – GPT-4o model used in ChatGPT.

### Cost-Optimized Models

- [GPT-4.1 mini](https://platform.openai.com/docs/models/gpt-4) – Balanced for intelligence, speed, and cost.
- [GPT-4.1 nano](https://platform.openai.com/docs/models/gpt-4) – Fastest, most cost-effective GPT-4.1 model.
- [GPT-4o mini](https://openai.com/index/gpt-4o) – Fast, affordable small model for focused tasks.
- [GPT-4o mini Audio Preview](https://openai.com/index/gpt-4o) – Smaller model capable of audio inputs and outputs.

### Realtime Models

- [GPT-4o Realtime Preview](https://openai.com/index/gpt-4o) – Realtime text and audio inputs and outputs.
- [GPT-4o mini Realtime Preview](https://openai.com/index/gpt-4o) – Smaller realtime model.

### Image Generation Models

- [GPT Image 1](https://openai.com/index/gpt-4o) – State-of-the-art image generation.
- [DALL·E 3](https://openai.com/dall-e) – Latest released version of DALL·E.
- [DALL·E 2](https://platform.openai.com/docs/guides/images) – Original image generation model.

### Text-to-Speech

- [GPT-4o mini TTS](https://openai.com/index/gpt-4o) – Text-to-speech powered by GPT-4o mini.
- [TTS-1](https://platform.openai.com/docs/guides/text-to-speech) – Optimized for speed.
- [TTS-1 HD](https://platform.openai.com/docs/guides/text-to-speech) – Optimized for quality.

### Transcription

- [GPT-4o Transcribe](https://openai.com/index/gpt-4o) – Speech-to-text powered by GPT-4o.
- [GPT-4o mini Transcribe](https://openai.com/index/gpt-4o) – Speech-to-text powered by GPT-4o mini.
- [Whisper](https://github.com/openai/whisper) – Open-source general-purpose speech recognition model.

### Tool-Specific Models

- [GPT-4o Search Preview](https://platform.openai.com/docs/guides/function-calling) – Optimized for web search.
- [GPT-4o mini Search Preview](https://platform.openai.com/docs/guides/function-calling) – Small, fast search model.
- [computer-use-preview](https://platform.openai.com/docs/guides/function-calling) – Specialized for computer control.
- [codex-mini-latest](https://platform.openai.com/docs/guides/code) – Fast model optimized for Codex CLI.

### Embeddings

- [text-embedding-3-small](https://platform.openai.com/docs/guides/embeddings) – Small embedding model.
- [text-embedding-3-large](https://platform.openai.com/docs/guides/embeddings) – Most capable embedding model.
- [text-embedding-ada-002](https://platform.openai.com/docs/guides/embeddings) – Legacy embedding model.

### Moderation

- [omni-moderation-latest](https://platform.openai.com/docs/guides/moderation) – Detect harmful content in text and images.
- [text-moderation-latest](https://platform.openai.com/docs/guides/moderation) – Text-only model (deprecated).

### Older GPT Models

- [GPT-4 Turbo](https://platform.openai.com/docs/models/gpt-4) – High-performance legacy GPT-4 variant.
- [GPT-4](https://platform.openai.com/docs/models/gpt-4) – Original GPT-4 release.
- [GPT-3.5 Turbo](https://platform.openai.com/docs/models/gpt-3-5) – Cost-effective legacy GPT model.

### GPT Base Models

- [babbage-002](https://platform.openai.com/docs/models/gpt-base) – Replacement for GPT-3 ada/babbage base models.
- [davinci-002](https://platform.openai.com/docs/models/gpt-base) – Replacement for GPT-3 curie/davinci base models.

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

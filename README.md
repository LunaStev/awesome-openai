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
- [OpenAI Documentation](https://platform.openai.com/docs) - Comprehensive guides and API references for OpenAI's models and tools.
- [OpenAI News](https://openai.com/news) - Product announcements, research papers, and updates.
- [OpenAI GitHub](https://github.com/openai) - Open-source tools and research by OpenAI.
- [OpenAI Help Center](https://help.openai.com/en/) - Support articles and FAQs for OpenAI services.
- [OpenAI Research](https://openai.com/research/) - Latest research publications and advancements from OpenAI.

## Getting Started

- [API Quickstart Guide](https://platform.openai.com/docs/quickstart) - Step-by-step guide to making your first API call.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Practical examples and guides for using the OpenAI API.
- [ChatGPT Custom GPTs](https://platform.openai.com/docs/guides/gpt) - Create and share your own GPTs tailored to specific tasks.
- [Whisper (Speech-to-Text)](https://github.com/openai/whisper) - Open-source automatic speech recognition system by OpenAI.

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

### Official SDKs

- [openai-python](https://github.com/openai/openai-python) - Official Python SDK for OpenAI API.
- [openai-node](https://github.com/openai/openai-node) - Official Node.js SDK for OpenAI API.
- [openai-go](https://github.com/openai/openai-go) - Official Go SDK for OpenAI API.
- [openai-ruby](https://github.com/openai/openai-ruby) - Official Ruby SDK for OpenAI API.
- [openai-java](https://github.com/openai/openai-java) - Official Java SDK for OpenAI API.
- [openai-dotnet](https://github.com/openai/openai-dotnet) - Official .NET SDK for OpenAI API.

### Community SDKs

- [openai-c](https://github.com/LunaStev/openai-c) - Unofficial C SDK for OpenAI API using libcurl and cJSON. Early-stage and chat endpoint only.
- [openai-cpp](https://github.com/olrea/openai-cpp) - Header-only C++ SDK for OpenAI API. Lightweight and easy to integrate.

### Frameworks & Tools

- [LangChain](https://github.com/langchain-ai/langchain) - Framework for building LLM-powered applications with modular components.
- [LlamaIndex](https://github.com/jerryjliu/llama_index) - Data framework for connecting LLMs to custom data sources.
- [Gradio](https://github.com/gradio-app/gradio) - UI library for building interactive machine learning demos.

## Developer Tools

- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) - Run code (Python, JavaScript, Shell, etc.) locally via natural language commands in a ChatGPT-like terminal interface.
- [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) - Autonomous GPT-4 agent that breaks down goals into sub-tasks and executes them independently.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - Specify what you want to build; the AI asks for clarification and then generates the entire codebase.
- [PromptLayer](https://github.com/MagnivOrg/prompt-layer-library) - Middleware for tracking, managing, and sharing GPT prompt engineering with analytics and version control.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Deploy autonomous AI agents in your browser, allowing them to perform tasks based on user-defined goals.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - A minimalistic autonomous AI agent that uses OpenAI and vector databases to perform tasks.
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - An open-source framework to develop, deploy, and manage autonomous AI agents.
- [Jarvis](https://github.com/microsoft/JARVIS) - Microsoft's project integrating LLMs with various tools to create a collaborative AI system.

## Prompts & Datasets

- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts) - A curated list of useful and creative prompts to inspire your ChatGPT interactions.
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - Comprehensive guide covering prompt engineering techniques, papers, and tools for large language models.
- [OpenAI Evals](https://github.com/openai/evals) - A framework for evaluating OpenAI models and an open-source registry of benchmarks.
- [PromptSource](https://github.com/bigscience-workshop/promptsource) - An integrated development environment and repository for natural language prompts.
- [HumanEval](https://github.com/openai/human-eval) - A benchmark for evaluating the problem-solving abilities of language models on code generation tasks.
- [Awesome Prompts](https://github.com/ai-boost/awesome-prompts) - A curated list of ChatGPT prompts from top-rated GPTs in the GPTs Store, including prompt engineering resources.
- [Prompt Engineering Guide (DAIR.AI)](https://www.promptingguide.ai/) - A web version of the Prompt Engineering Guide, offering structured learning materials and resources.
- [ChatGPT Prompts Library](https://github.com/topics/chatgpt-prompts) - A diverse collection of over 100,000 prompts tailored for ChatGPT, covering various topics and use cases.

## Papers & Research

- [GPT-4 Technical Report](https://openai.com/research/gpt-4) - Detailed technical report on GPT-4's architecture, capabilities, and evaluation benchmarks.
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) - Seminal paper introducing GPT-3 and demonstrating its few-shot learning abilities.
- [Function Calling with GPT](https://openai.com/blog/function-calling-and-other-api-updates) - Overview of OpenAI's function calling feature, enabling models to call external functions.
- [GPT-4 System Card](https://openai.com/index/gpt-4o-system-card/) - Comprehensive analysis of GPT-4's capabilities, limitations, and safety evaluations.
- [Finetuned Language Models Are Zero-Shot Learners](https://arxiv.org/abs/2109.01652) - Study on instruction-tuned models achieving strong zero-shot performance.
- [Bidirectional Language Models Are Also Few-shot Learners](https://arxiv.org/abs/2209.14500) - Research showing that bidirectional models can perform few-shot learning effectively.

## Projects Using OpenAI

- [Notion AI](https://www.notion.so/product/ai) - Enhances productivity with AI-powered writing, summarization, and Q&A features integrated into Notion's workspace.
- [GitHub Copilot](https://github.com/features/copilot) - AI pair programmer that suggests code snippets and entire functions in real-time within your IDE.
- [ChatGPT Plugins](https://openai.com/blog/chatgpt-plugins) - Extend ChatGPT's capabilities by integrating third-party services and tools directly into the chat interface.
- [Replit Ghostwriter](https://replit.com/site/ghostwriter) - AI coding assistant in Replit that helps with code completion, explanation, and transformation within the IDE.
- [Duolingo Max](https://www.duolingo.com/) - Language learning platform that uses GPT-4 to provide AI-powered explanations and interactive exercises.
- [Khanmigo by Khan Academy](https://www.khanacademy.org/) - AI tutor powered by GPT-4 that assists students with personalized learning experiences.
- [Shopify Sidekick](https://www.shopify.com/) - AI assistant for Shopify merchants that helps with store management and customer interactions.
- [Zapier AI](https://zapier.com/) - Automates workflows by integrating OpenAI's language models to interpret natural language commands.
- [GrammarlyGO](https://www.grammarly.com/) - AI writing assistant that leverages OpenAI's models to enhance writing clarity and tone.
- [Slack GPT](https://slack.com/) - Integrates GPT models into Slack to provide AI-powered conversation summaries and assistance.

## Community

- [OpenAI Community Forum](https://community.openai.com) - Official discussion board for OpenAI users and developers.
- [Discord (Unofficial)](https://discord.gg/openai) - Unofficial but active Discord server for OpenAI enthusiasts.
- [r/OpenAI](https://reddit.com/r/OpenAI) - Subreddit for sharing news, experiments, and questions related to OpenAI.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/openai) - Q&A for OpenAI API usage and development issues.
- [Twitter/X - #OpenAI](https://twitter.com/hashtag/OpenAI) - Real-time discussions, updates, and community showcases.
- [Hugging Face Forums](https://discuss.huggingface.co/c/openai/27) - Community conversations around using OpenAI models via Hugging Face.

---

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

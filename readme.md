# Awesome Computer Use [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome computer use agents, OS automation engines, GUI grounding models, benchmarks, and protocols.

Computer use refers to artificial intelligence agents and multimodal models capable of visually observing graphical user interfaces (GUI), reasoning over visual elements, and directly actuating operating systems (Linux, macOS, Windows) through native mouse, keyboard, and accessibility interfaces like human users.

## Contents

- [Desktop and OS Automation Engines](#desktop-and-os-automation-engines)
- [Multimodal GUI Grounding Models](#multimodal-gui-grounding-models)
- [Agent Frameworks and Orchestrators](#agent-frameworks-and-orchestrators)
- [Benchmarks and Evaluation Environments](#benchmarks-and-evaluation-environments)
- [Protocols and Accessibility Interfaces](#protocols-and-accessibility-interfaces)
- [Datasets and Pretraining Corpora](#datasets-and-pretraining-corpora)
- [Research Papers and Surveys](#research-papers-and-surveys)

## Desktop and OS Automation Engines

- [Anthropic Computer Use](https://github.com/anthropics/anthropic-quickstarts/tree/main/computer-use-demo) - Reference implementation for Claude 3.5 Sonnet's native desktop automation capabilities.
- [Cradle](https://github.com/baai-agents/Cradle) - General computer control framework enabling agents to master commercial software and complex desktop games.
- [Extra](https://github.com/AIYantra/extra) - Sovereign desktop automation engine and MCP server featuring hardware-level human actuation, visual grounding, and Dual-Plane execution.
- [Open-Interpreter](https://github.com/openinterpreter/open-interpreter) - Open-source, locally executing implementation of OpenAI's Code Interpreter for computer control.
- [OS-Copilot](https://github.com/OS-Copilot/OS-Copilot) - Autonomous agent system capable of interacting with diverse operating system elements across Linux, macOS, and Windows.
- [UFO](https://github.com/microsoft/UFO) - Dual-agent OS automation system developed by Microsoft for seamless Windows application control.

## Multimodal GUI Grounding Models

- [CogAgent](https://github.com/THUDM/CogVLM) - Visual language foundation model specialized for GUI understanding and navigation across desktop and mobile.
- [Ferret-UI](https://github.com/apple/ml-ferret) - Multimodal large language model tailored by Apple for mobile and desktop user interface screen understanding.
- [Fuyu-8B](https://www.adept.ai/blog/fuyu-8b) - Small, fast multimodal architecture designed by Adept AI for screen parsing and agentic action generation.
- [OmniParser](https://github.com/microsoft/OmniParser) - Screen parsing tool by Microsoft that converts UI screenshots into structured icon, text, and bounding-box graphs.
- [OS-Atlas](https://github.com/OS-Copilot/OS-Atlas) - Foundation action model tailored for cross-platform GUI grounding across operating systems and the web.
- [SeeClick](https://github.com/nju-websoft/SeeClick) - Visual grounding model for GUI agent actions through direct coordinate prediction.
- [ShowUI](https://github.com/showlab/ShowUI) - Lightweight vision-language model trained for high-resolution visual desktop and web grounding.
- [UI-TARS](https://github.com/bytedance/UI-TARS) - End-to-end GUI agent model developed by ByteDance with native OS actuation and visual reasoning capabilities.

## Agent Frameworks and Orchestrators

- [Agent-S](https://github.com/simular-ai/Agent-S) - Autonomous GUI agent framework featuring hierarchical planning and multi-modal experience learning.
- [BrowserGym](https://github.com/ServiceNow/BrowserGym) - Ecosystem of web environments and benchmark interfaces for evaluating computer-use agents.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Collaborative multi-agent orchestration framework supporting autonomous desktop tool use.
- [LangChain](https://github.com/langchain-ai/langchain) - Framework for building context-aware reasoning applications and tool-calling computer agents.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework connecting custom data sources with agent toolkits and operating system actions.

## Benchmarks and Evaluation Environments

- [AndroidWorld](https://github.com/google-research/android_world) - Dynamic, fully interactive benchmarking environment developed by Google for mobile UI agents.
- [OSWorld](https://github.com/xlang-ai/OSWorld) - Multimodal benchmark for evaluating open-ended computer tasks in real operating system environments.
- [ScreenSpot](https://github.com/nju-websoft/ScreenSpot) - Benchmark for evaluating GUI visual grounding accuracy across desktop, mobile, and web interfaces.
- [VisualWebArena](https://github.com/web-arena-x/visualwebarena) - Multi-modal web benchmark for evaluating autonomous visual agents on complex realistic web tasks.
- [WebArena](https://github.com/web-arena-x/webarena) - Realistic web environment benchmark assessing autonomous agent capabilities across e-commerce, forums, and developer tools.
- [WindowsArena](https://github.com/microsoft/WindowsArena) - Benchmarking platform created by Microsoft for evaluating computer-use agents on Windows OS tasks.

## Protocols and Accessibility Interfaces

- [Accessibility API (AT-SPI2)](https://gitlab.gnome.org/GNOME/at-spi2-core) - Standard Assistive Technology Service Provider Interface enabling semantic GUI accessibility on Linux desktops.
- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) - Open standard developed by Anthropic for connecting AI models to desktop environments and external developer tools.
- [UIAutomation (Win32 UIA)](https://learn.microsoft.com/en-us/windows/win32/winauto/entry-uiauto-win32) - Microsoft Windows accessibility framework enabling programmatic UI inspection and event dispatch.

## Datasets and Pretraining Corpora

- [AITW (Android-in-the-Wild)](https://github.com/google-research/google-research/tree/master/android_in_the_wild) - Large-scale dataset of human device interactions across Android applications.
- [GUI-Act](https://huggingface.co/datasets/bytedance-research/GUI-Act) - Diverse dataset of desktop, mobile, and web trajectories for training multimodal computer agents.
- [Mind2Web](https://github.com/OSU-NLP-Group/Mind2Web) - Dataset for developing and evaluating generalist web agents across multi-domain tasks.

## Research Papers and Surveys

- [A Survey on Computer Use Agents](https://arxiv.org/abs/2411.00000) - Comprehensive survey of vision-language models and reinforcement learning frameworks for GUI automation.
- [OSWorld: Benchmarking Multimodal Agents on OS](https://arxiv.org/abs/2404.07972) - Foundational paper introducing real-world multimodal operating system task benchmarks.
- [UI-TARS: An End-to-End GUI Agent](https://arxiv.org/abs/2501.12332) - Architecture and empirical results for native vision-language computer control.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](contributing.md) first.

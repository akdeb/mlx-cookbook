# [awesome-mlx](https://github.com/akdeb/awesome-mlx)

A curated list of awesome MLX projects that run on Apple Silicon Macs.

Platform note: MLX targets Apple silicon, so these are Mac-focused projects.

If you want to add your project, open a PR. Projects with some traction will be added.

## Core MLX & Examples

- [mlx](https://github.com/ml-explore/mlx): MLX: An array framework for Apple silicon
- [mlx-examples](https://github.com/ml-explore/mlx-examples): Examples in the MLX framework
- [mlx-lm](https://github.com/ml-explore/mlx-lm): Run LLMs with MLX
- [mlx-swift-examples](https://github.com/ml-explore/mlx-swift-examples): Examples using MLX Swift
- [mlx-swift](https://github.com/ml-explore/mlx-swift): Swift API for MLX
- [speech-swift](https://github.com/soniqo/speech-swift): AI speech toolkit for Apple Silicon - ASR, TTS, speech-to-speech, VAD, and diarization powered by MLX and CoreML
- [mlx-swift-chat](https://github.com/preternatural-explore/mlx-swift-chat): A multi-platform SwiftUI frontend for running local LLMs with Apple's MLX framework.
- [mlx-c](https://github.com/ml-explore/mlx-c): C API for MLX
- [mlx-swift-audio](https://github.com/DePasqualeOrg/mlx-swift-audio): Swift tools for text to speech (TTS) and speech to text (STT) powered by MLX

## LLM & Inference

- [llmfit](https://github.com/AlexsJones/llmfit): Hundreds of models & providers. One command to find what runs on your hardware.
- [omlx](https://github.com/jundot/omlx): LLM inference server with continuous batching & SSD caching for Apple Silicon - managed from the macOS menu bar
- [osaurus](https://github.com/osaurus-ai/osaurus): Own your AI. The native macOS harness for AI agents -- any model, persistent memory, autonomous execution, cryptographic identity. Built in Swift. Fully offline. Open source.
- [mlx-vlm](https://github.com/Blaizzy/mlx-vlm): MLX-VLM is a package for inference and fine-tuning of Vision Language Models (VLMs) on your Mac using MLX.
- [Klee](https://github.com/signerlabs/Klee): A native macOS AI chat app powered by MLX. 100% local inference on Apple Silicon, no cloud required. Built with ShipSwift.
- [mlx-tune](https://github.com/ARahim3/mlx-tune): Fine-tune LLMs on your Mac with Apple Silicon. SFT, DPO, GRPO, and Vision fine-tuning - natively on MLX. Unsloth-compatible API.
- [ChatMLX](https://github.com/johnmai-dev/ChatMLX): 🤖✨ChatMLX is a modern, open-source, high-performance chat application for MacOS based on large language models.
- [vllm-mlx](https://github.com/waybarrios/vllm-mlx): OpenAI and Anthropic compatible server for Apple Silicon. Run LLMs and vision-language models (Llama, Qwen-VL, LLaVA) with continuous batching, MCP tool calling, and multimodal support. Native MLX backend, 400+ tok/s. Works with Claude Code.
- [mlx-omni-server](https://github.com/madroidmaq/mlx-omni-server): MLX Omni Server is a local inference server powered by Apple's MLX framework, specifically designed for Apple Silicon (M-series) chips. It implements OpenAI-compatible API endpoints, enabling seamless integration with existing OpenAI SDK clients while leveraging the power of local ML inference.
- [mlx-llm](https://github.com/riccardomusmeci/mlx-llm): Large Language Models (LLMs) applications and tools running on Apple Silicon in real-time with Apple MLX.
- [qwen3-tts-apple-silicon](https://github.com/kapi2800/qwen3-tts-apple-silicon): Run Qwen3-TTS text-to-speech locally on Mac (M1/M2/M3/M4). Voice cloning, voice design, custom voices. 100% offline using MLX.
- [NotebookMLX](https://github.com/johnmai-dev/NotebookMLX): 📋 NotebookMLX - An Open Source version of NotebookLM (Ported NotebookLlama)
- [PicoMLXServer](https://github.com/PicoMLX/PicoMLXServer): The easiest way to run the fastest MLX-based LLMs locally
- [nodetool](https://github.com/nodetool-ai/nodetool): Visual Builder for AI Workflows and Agents
- [SiLLM](https://github.com/armbues/SiLLM): SiLLM simplifies the process of training and running Large Language Models (LLMs) on Apple Silicon by leveraging the MLX framework.
- [maclocal-api](https://github.com/scouzi1966/maclocal-api): 'afm' command cli: macOS server and single prompt mode that exposes Apple's Foundation and MLX Models and other APIs running on your Mac through a single aggregated OpenAI-compatible API endpoint. Supports Apple Vision and single command (non-server) inference with piping as well . Now with Web Browser and  local AI API aggregator
- [mlx-gui](https://github.com/RamboRogers/mlx-gui): MLX-GUI MLX Inference Server for Apple Silicone
- [pmetal](https://github.com/Epistates/pmetal): Powdered Metal - High performance LLM fine-tuning framework for Apple Silicon
- [mlxstudio](https://github.com/jjang-ai/mlxstudio): MLX Studio - Home of JANG_Q - Image Gen/Edit + Chat/Code All in one - + OpenClaw (Anthropic API)
- [LocalLLMClient](https://github.com/tattn/LocalLLMClient): Swift package to run local LLMs on iOS, macOS, Linux
- [olla](https://github.com/thushan/olla): High-performance lightweight proxy and load balancer for LLM infrastructure. Intelligent routing, automatic failover and unified model discovery across local and remote inference backends.
- [QwenVoice](https://github.com/PowerBeef/QwenVoice): Native macOS app for Qwen3-TTS with custom voices, voice design, and voice cloning, 100% offline on Apple Silicon
- [pyOllaMx](https://github.com/kspviswa/pyOllaMx): Your gateway to both Ollama & Apple MlX models
- [Toolio](https://github.com/OoriData/Toolio): GenAI & agent toolkit for Apple Silicon Mac, implementing JSON schema-steered structured output (3SO) and tool-calling in Python. For more on 3SO: https://huggingface.co/blog/ucheog/llm-power-steering
- [wine_variety_classification](https://github.com/ivanfioravanti/wine_variety_classification): Examples on how to use various LLM providers with a Wine Classification problem
- [anubis-oss](https://github.com/uncSoft/anubis-oss): Local LLM Testing & Benchmarking for Apple Silicon
- [llamactl](https://github.com/lordmathis/llamactl): Unified management and routing for llama.cpp, MLX and vLLM models with web dashboard.
- [mlx_sharding](https://github.com/mzbac/mlx_sharding): Distributed Inference for mlx LLm

## Audio & Speech

- [voicebox](https://github.com/jamiepine/voicebox): The open-source voice synthesis studio
- [mlx-audio](https://github.com/Blaizzy/mlx-audio): A text-to-speech (TTS), speech-to-text (STT) and speech-to-speech (STS) library built on Apple's MLX framework, providing efficient speech analysis on Apple Silicon.
- [TheWhisper](https://github.com/TheStageAI/TheWhisper): Optimized Whisper models for streaming and on-device use
- [f5-tts-mlx](https://github.com/lucasnewman/f5-tts-mlx): Implementation of F5-TTS in MLX
- [mlx-audio-swift](https://github.com/Blaizzy/mlx-audio-swift): A modular Swift SDK for audio processing with MLX on Apple Silicon
- [wtm](https://github.com/JosefAlbers/wtm): Blazing fast whisper turbo for ASR (speech-to-text) tasks
- [kokoro-ios](https://github.com/mlalma/kokoro-ios): Kokoro TTS for iOS and macOSX
- [nanospeech](https://github.com/lucasnewman/nanospeech): A simple, hackable text-to-speech system in PyTorch and MLX
- [whisply](https://github.com/tsmdt/whisply): 💬 Fast, cross-platform CLI and GUI for batch transcription, translation, speaker annotation and subtitle generation using OpenAI’s Whisper on CPU, Nvidia GPU and Apple MLX.

## Vision & Multimodal

- [mflux](https://github.com/filipstrand/mflux): MLX native implementations of state-of-the-art generative image models
- [sisi](https://github.com/frost-beta/sisi): Semantic Image Search CLI tool.
- [photo-similarity-search](https://github.com/harperreed/photo-similarity-search): Super simple MLX (apple silicon) CLIP based photo similarity web app
- [Fabric](https://github.com/Fabric-Project/Fabric): Node Creative Coding / 3D / Image Processing tool inspired by Quartz Composer
- [MLX-Auto-Subtitled-Video-Generator](https://github.com/RayFernando1337/MLX-Auto-Subtitled-Video-Generator): Generate accurate transcripts using Apple's MLX framework
- [mlx-openai-server](https://github.com/cubist38/mlx-openai-server): A high-performance API server that provides OpenAI-compatible endpoints for MLX models. Developed using Python and powered by the FastAPI framework, it provides an efficient, scalable, and user-friendly solution for running MLX-based vision and language models locally with an OpenAI-compatible interface.
- [pvm](https://github.com/JosefAlbers/pvm): Phi-3.5 for Mac: Locally-run Vision and Language Models for Apple Silicon
- [MLX-Outil](https://github.com/rudrankriyam/MLX-Outil): Tool calling using MLX Swift across iOS, macOS, and visionOS platforms
- [SAM](https://github.com/SyntheticAutonomicMind/SAM): Synthetic Autonomic Mind - An AI assistant for everyone.
- [images_example](https://github.com/keuhdall/images_example): A simple example program made for the 42 students going into the graphic branch. Its purpose is to help them understanding the way images are working in the MLX (the graphcal lib we use).
- [miniLibX_sample](https://github.com/S-LucasSerrano/miniLibX_sample): Well-organized, commented and documented sample project that shows the basic functionalities of the 42's mlx library.

## Training, Fine-tuning & Optimization

- [transformerlab-app](https://github.com/transformerlab/transformerlab-app): The open source research environment for AI researchers to seamlessly train, evaluate, and scale models from local hardware to GPU clusters.
- [mlx-benchmark](https://github.com/TristanBilot/mlx-benchmark): Benchmark of Apple MLX operations on all Apple Silicon chips (GPU, CPU) + MPS and CUDA.
- [mlx-retrieval](https://github.com/jina-ai/mlx-retrieval): Train embedding and reranker models for retrieval tasks on Apple Silicon with MLX

## Apps, UI & Tooling

- [ml-aim](https://github.com/apple/ml-aim): This repository provides the code and model checkpoints for AIMv1 and AIMv2 research projects.
- [mlx-engine](https://github.com/lmstudio-ai/mlx-engine): LM Studio Apple MLX engine
- [mlx-ui](https://github.com/da-z/mlx-ui): A simple UI / Web / Frontend for MLX mlx-lm using Streamlit.
- [jina-grep-cli](https://github.com/jina-ai/jina-grep-cli): Semantic grep powered by Jina embeddings v5 (MLX on Apple Silicon)
- [MFLUX-WEBUI](https://github.com/CharafChnioune/MFLUX-WEBUI): MFLUX-WEBUI using MLX and the FLUX DEV and Schnell models

## Other

- [einops](https://github.com/arogozhnikov/einops): Flexible and powerful tensor operations for readable and reliable code (for pytorch, jax, TF and others)
- [AirPosture](https://github.com/allenv0/AirPosture): AirPods as AI posture coach on iOS  (launching 2026)
- [Metal-Puzzles](https://github.com/abeleinin/Metal-Puzzles): Solve Puzzles. Learn Metal 🤘
- [MLX42](https://github.com/codam-coding-college/MLX42): Codam's own fixed, functioning and open source alternative of the miniLibX. MLX42 is a simple cross-platform graphics library running on GLFW and OpenGL.
- [node-mlx](https://github.com/frost-beta/node-mlx): Machine learning framework for Node.js.
- [Vim-LM](https://github.com/JosefAlbers/Vim-LM): AI Copilot for Vim/NeoVim
- [mlx](https://github.com/claimed-framework/mlx): Machine Learning eXchange (MLX). Data and AI Assets Catalog and Execution Engine
- [mlx_example](https://github.com/terry-yes/mlx_example): Some examples for those who try to use MLX library for 42 subject CUB3D or miniRT. And some helpful links.
- [lilm](https://github.com/alphrc/lilm): Large language model fine-tuned to mimic LIHKG users' behavior

## Rising projects

- [Eris.](https://github.com/Natxo09/Eris.): Eris is a private AI chat application that runs entirely on your device using Apple's MLX framework. Named after the dwarf planet that challenged our understanding of the solar system, Eris challenges the notion that AI must live in the cloud.
- [m-courtyard](https://github.com/Mcourtyard/m-courtyard): M-Courtyard: Local AI Model Fine-tuning Assistant for Apple Silicon. Zero-code, zero-cloud, privacy-first desktop app powered by Tauri + React + mlx-lm.
- [SEIR](https://github.com/ECheynet/SEIR): Generalized SEIR Epidemic Model (fitting and computation)
- [f5-tts-swift](https://github.com/lucasnewman/f5-tts-swift): Implementation of F5-TTS in Swift using MLX
- [vmlx](https://github.com/jjang-ai/vmlx): vMLX - Home of JANG_Q - Cont Batch, Prefix, Paged, KV Cache Quant, VL - Powers MLX Studio. Image gen/edit, OpenAI/Anth
- [PyOMlx](https://github.com/kspviswa/PyOMlx): A wannabe Ollama equivalent for Apple MlX models
- [mlx_clip](https://github.com/harperreed/mlx_clip): A simple package to use CLIP on apple silicon using the MLX libraries from Apple
- [Conduit](https://github.com/christopherkarani/Conduit): 🦑 Unified Swift SDK for LLM inference across local and cloud providers
- [flux-generator](https://github.com/voipnuggets/flux-generator): Local image and music generation for Apple Silicon
- [mlx-vis](https://github.com/hanxiao/mlx-vis): Pure MLX implementations of UMAP, t-SNE, PaCMAP, TriMap, DREAMS, CNE, MMAE, and NNDescent for Apple Silicon. Metal GPU for computation and video rendering.
- [llama3.js](https://github.com/frost-beta/llama3.js): A JavaScript implementation of Llama 3 using node-mlx.
- [codec](https://github.com/AVADSA25/codec): Open-Source Intelligent Command Layer
- [vesta-mac-dist](https://github.com/scouzi1966/vesta-mac-dist): Vesta macOS Distribution - Official releases and downloads.Vesta AI Chat Assistant for macOS - Built with SwiftUI, Swift MLX  and Apple Intelligence using Apple's on device model on MacOs Tahoe (MacOS 26). Now with side-by-side Qwen3-VL for vison
- [mlx-flash](https://github.com/matt-k-wong/mlx-flash): Flash weight streaming for MLX: run massive models larger than your RAM on Apple Silicon.
- [sentinel-reverse](https://github.com/sgInnora/sentinel-reverse): AI-Powered Autonomous Binary Reverse Engineering CLI - the native reverse engine from Innora-Sentinel. Local LLM inference (MLX), MPS GPU acceleration, multi-round iterative analysis, zero API cost.
- [cactus-flutter](https://github.com/cactus-compute/cactus-flutter): Cactus Flutter plugin: Run AI locally in your Flutter apps
- [jangq](https://github.com/jjang-ai/jangq): JANG - GGUF for MLX. YOU MUST USE JANG_Q RUNTIME. Adaptive Mixed-Precision Quantization + Runtime for Apple Silicon
- [web3-ai-trading-agent](https://github.com/chainstacklabs/web3-ai-trading-agent): Build an Autonomous Web3 AI Trading Agent (BASE + Uniswap V4 example)
- [so_long](https://github.com/S-LucasSerrano/so_long): Small game developed with the miniLibX, the graphic library of the 42 school.
- [open-toys](https://github.com/akdeb/open-toys): Local, Free CharacterAI with inference on Apple Silicon and ESP32 WebSocket transport
- [mlx-optimizers](https://github.com/stockeh/mlx-optimizers): A collection of optimizers for MLX
- [So_Long](https://github.com/Florian-A/So_Long): Et merci pour les pièces !
- [universal-intelligence](https://github.com/blueraai/universal-intelligence): ◉ Universal Intelligence: AI made simple.
- [MLX-Transcribe](https://github.com/RamboRogers/MLX-Transcribe): Instant Perfect Native MacOS Transcription
- [MLX_z-image](https://github.com/uqer1244/MLX_z-image): MLX version of z-image model
- [turboquant-mlx](https://github.com/arozanov/turboquant-mlx): TurboQuant KV cache compression for MLX with fused Metal kernels. 4.6x compression at 98% FP16 speed.
- [offline-voice-ai](https://github.com/shubhdotai/offline-voice-ai): FastAPI + MLX offline-first voice agent with <1s latency. Minimal UI
- [Glosik](https://github.com/rudrankriyam/Glosik): Sample project for F5-TTS using MLX Swift

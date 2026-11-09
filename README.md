# ⚡ Awesome WebGPU AI & In-Browser Machine Learning (2026)

> **A verified, live-monitored directory of client-side WebGPU runtimes, in-browser LLMs, audio/vision models, and zero-server AI architectures.**
> *Updated automatically every 24 hours with live health-checks and latency benchmarks.*

[![Uptime](https://img.shields.io/badge/Monitored_Uptime-100.0%25-3fb950?style=for-the-badge&logo=statuspage)](https://github.com/dhaulagani/awesome-webgpu-ai) [![Verified Frameworks](https://img.shields.io/badge/Verified_Frameworks-22_Active-58a6ff?style=for-the-badge)](https://github.com/dhaulagani/awesome-webgpu-ai) [![Last Verified](https://img.shields.io/badge/Last_Check-2026-11-07_18:06_UTC-brightgreen?style=for-the-badge)](https://github.com/dhaulagani/awesome-webgpu-ai)

---

### 💡 Why WebGPU AI is Transforming Software Engineering
Cloud API tokens for LLMs and GPUs impose heavy recurring expenses and latency bottlenecks.
With **WebGPU now active by default** across modern browsers (Google Chrome, Microsoft Edge, Safari, Firefox), developers can execute generative AI models **100% locally on the user's GPU**:
- 💸 **Zero Server Bill**: Run complex LLM inference, vector embedding, and transcription with **$0 cloud compute costs**.
- 🔒 **100% Privacy by Design**: Sensitive user data, audio recordings, and confidential documents never leave the client device.
- ⚡ **Instant Zero-Network Latency**: Direct hardware GPU acceleration via WebAssembly and WGSL shaders.

---

## 📑 Table of Contents
- [In-Browser LLM & ML Runtimes](#in-browser-llm-ml-runtimes)
- [Speech & Voice WebGPU Models](#speech-voice-webgpu-models)
- [Computer Vision & Diffusion WebGPU](#computer-vision-diffusion-webgpu)
- [Client-Side Embeddings & Zero-Cloud RAG](#client-side-embeddings-zero-cloud-rag)
- [Edge Models & Developer Toolkits](#edge-models-developer-toolkits)

---
## In-Browser LLM & ML Runtimes

| Framework / Tool | Core Client-Side Capability | Runtime Tech | Health & Latency | Source & Demo |
| :--- | :--- | :---: | :--- | :--- |
| [WebLLM (MLC-LLM)](https://webllm.mlc.ai) | High-performance in-browser LLM engine running Llama 3, Gemma, Mistral & Qwen with WebGPU acceleration | `WebGPU / WebAssembly` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 447ms` | [**GitHub / Docs ↗**](https://github.com/mlc-ai/web-llm) |
| [Transformers.js v3 (Hugging Face)](https://huggingface.co/docs/transformers.js) | State-of-the-art WebGPU-accelerated JavaScript library for text, vision, and audio foundation models | `WebGPU / ONNX Runtime Web` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 119ms` | [**GitHub / Docs ↗**](https://github.com/huggingface/transformers.js) |
| [Wllama](https://github.com/ngxson/wllama) | llama.cpp compiled directly to WebAssembly + WebGPU bindings for ultra-low overhead GGUF model execution | `Wasm + WebGPU` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 627ms` | [**GitHub / Docs ↗**](https://github.com/ngxson/wllama) |
| [ONNX Runtime Web (Microsoft)](https://onnxruntime.ai) | Cross-platform hardware-accelerated inference engine supporting WebGPU kernels for all ONNX models | `WebGPU / WebAssembly` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 377ms` | [**GitHub / Docs ↗**](https://github.com/microsoft/onnxruntime) |
| [Ratchet](https://github.com/FL33TW00D/ratchet) | High-performance Rust-native deep learning engine targeting WebGPU for instant client-side execution | `Rust / WebGPU` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 1076ms` | [**GitHub / Docs ↗**](https://github.com/FL33TW00D/ratchet) |
| [Candle (Wasm)](https://github.com/huggingface/candle) | Minimalist, highly optimized machine learning framework for Rust supporting browser WASM and WebGPU | `Rust / Wasm / WebGPU` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 571ms` | [**GitHub / Docs ↗**](https://github.com/huggingface/candle) |

## Speech & Voice WebGPU Models

| Framework / Tool | Core Client-Side Capability | Runtime Tech | Health & Latency | Source & Demo |
| :--- | :--- | :---: | :--- | :--- |
| [Whisper-Web](https://github.com/xenova/whisper-web) | Real-time speech-to-text recognition running 100% locally in browser with WebGPU hardware acceleration | `Transformers.js / WebGPU` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 606ms` | [**GitHub / Docs ↗**](https://github.com/xenova/whisper-web) |
| [Kokoro-JS (Kokoro-82M Web)](https://github.com/hexgrad/kokoro) | 82M parameter state-of-the-art TTS running in the browser generating natural voice audio in real-time | `WebGPU / ONNX` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 532ms` | [**GitHub / Docs ↗**](https://github.com/hexgrad/kokoro) |
| [Distil-Whisper WebGPU](https://huggingface.co/distil-whisper) | Distilled, lightweight Whisper variants operating at 6x speed in browser with minimal memory overhead | `WebGPU` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 348ms` | [**GitHub / Docs ↗**](https://github.com/huggingface/distil-whisper) |
| [Silero VAD Web](https://github.com/snakers4/silero-vad) | Sub-millisecond Voice Activity Detection (VAD) running client-side to detect speech pauses and turns | `ONNX Runtime Web` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 548ms` | [**GitHub / Docs ↗**](https://github.com/snakers4/silero-vad) |

## Computer Vision & Diffusion WebGPU

| Framework / Tool | Core Client-Side Capability | Runtime Tech | Health & Latency | Source & Demo |
| :--- | :--- | :---: | :--- | :--- |
| [Segment Anything (SAM) Web](https://github.com/facebookresearch/segment-anything) | Meta's foundational image segmentation running zero-shot point-and-click masks in browser via WebGPU | `ONNX Runtime Web` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 538ms` | [**GitHub / Docs ↗**](https://github.com/facebookresearch/segment-anything) |
| [Florence-2 WebGPU](https://huggingface.co/microsoft/Florence-2-base) | Microsoft's compact vision-language foundation model for image captioning, OCR, and object grounding | `Transformers.js / WebGPU` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 147ms` | [**GitHub / Docs ↗**](https://github.com/microsoft/Florence-2-base) |
| [Depth Anything WebGPU](https://github.com/LiheYoung/Depth-Anything) | Highly robust monocular depth estimation running directly inside the client browser canvas | `ONNX Runtime Web` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 609ms` | [**GitHub / Docs ↗**](https://github.com/LiheYoung/Depth-Anything) |
| [Web-Stable-Diffusion](https://github.com/mlc-ai/web-stable-diffusion) | Complete Stable Diffusion text-to-image latent pipeline generating images 100% on the client GPU | `WebGPU / WebAssembly` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 616ms` | [**GitHub / Docs ↗**](https://github.com/mlc-ai/web-stable-diffusion) |

## Client-Side Embeddings & Zero-Cloud RAG

| Framework / Tool | Core Client-Side Capability | Runtime Tech | Health & Latency | Source & Demo |
| :--- | :--- | :---: | :--- | :--- |
| [Voy (Wasm Vector DB)](https://github.com/tantaraio/voy) | Wasm-native vector search engine powering fast nearest-neighbor semantic search entirely in the browser | `Wasm` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 562ms` | [**GitHub / Docs ↗**](https://github.com/tantaraio/voy) |
| [all-MiniLM-L6-v2 WebGPU](https://huggingface.co/Xenova/all-MiniLM-L6-v2) | Compact dense sentence embeddings running locally in browser to index documents for private RAG | `Transformers.js / WebGPU` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 100ms` | [**GitHub / Docs ↗**](https://huggingface.co/Xenova/all-MiniLM-L6-v2) |
| [BGE-Micro-v2 Web](https://huggingface.co/BAAI/bge-small-en-v1.5) | State-of-the-art embedding model quantized for fast sub-50ms text vectorization on client devices | `WebGPU` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 98ms` | [**GitHub / Docs ↗**](https://huggingface.co/BAAI/bge-small-en-v1.5) |
| [MiniSearch](https://github.com/lucaong/minisearch) | Ultra-lightweight in-memory client-side full-text search engine with fuzzy search and prefix matching | `Pure JavaScript` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 626ms` | [**GitHub / Docs ↗**](https://github.com/lucaong/minisearch) |

## Edge Models & Developer Toolkits

| Framework / Tool | Core Client-Side Capability | Runtime Tech | Health & Latency | Source & Demo |
| :--- | :--- | :---: | :--- | :--- |
| [SmolLM2 (Hugging Face)](https://huggingface.co/HuggingFaceTB/SmolLM2-135M) | Family of 135M, 360M, and 1.7B parameter models engineered specifically for edge and in-browser inference | `WebGPU / ONNX` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 168ms` | [**GitHub / Docs ↗**](https://github.com/huggingface/smollm) |
| [Vercel AI SDK Client](https://sdk.vercel.ai) | Unified frontend framework for streaming AI completions with seamless client-side runtime switching | `TypeScript` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 366ms` | [**GitHub / Docs ↗**](https://github.com/vercel/ai) |
| [Chrome Built-in Prompt API (Gemini Nano)](https://developer.chrome.com/docs/ai/built-in) | Experimental native browser API providing zero-download local Gemini Nano model execution in Chrome | `Native Browser Engine` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 1225ms` | [**GitHub / Docs ↗**](https://github.com/webmachinelearning/prompt-api) |
| [WebGPU Shaders & WGSL Matrix Kernels](https://www.w3.org/TR/webgpu/) | W3C official WebGPU standard specifications, compute shaders, and low-level hardware interface | `WGSL / WebGPU Standard` | ![Online](https://img.shields.io/badge/Status-Online-3fb950?style=flat-square) `⚡ 93ms` | [**GitHub / Docs ↗**](https://github.com/gpuweb/gpuweb) |

---

## 🏗️ Architectural Topology: The Zero-Cloud Client AI Stack

```
+-------------------------------------------------------------------------+
|                    CLIENT APPLICATION (HTML / REACT / VUE)              |
+-------------------------------------------------------------------------+
             |                                          |                  
             v                                          v                  
+-------------------------+                +-------------------------+     
|   IN-BROWSER VECTOR DB  |                |   CLIENT SPEECH & AUDIO |     
|  (Voy, MiniSearch,      | <------------> |   (Whisper-Web, Kokoro, |     
|   all-MiniLM Embeddings)|   Zero-Server  |    Silero VAD)          |     
+-------------------------+       RAG      +-------------------------+     
             |                                          |                  
             +--------------------+---------------------+                  
                                  v                                        
               +-------------------------------------+                     
               |      WEBGPU HARDWARE ACCELERATION   |                     
               | (WebLLM, Transformers.js, Wllama,   |                     
               |  ONNX Runtime Web, Ratchet WGSL)    |                     
               +-------------------------------------+                     
                                  |                                        
                                  v                                        
               +-------------------------------------+                     
               |  USER LOCAL GPU (DirectX, Metal, VK)|                     
               +-------------------------------------+                     
```

## 🤖 How the Autonomous Verification Engine Works
This repository is maintained automatically by a background verification daemon:
1. Every 24 hours, an automated runner sends latency probes and handshake pings to each framework's primary repository and documentation portal.
2. Frameworks with breaking deprecations, licensing shifts, or archived repositories are flagged and revised.
3. Live badges and latency benchmarks (`ms`) are re-computed and committed directly to `main` via GitHub Actions with concurrency locks.

## 🤝 Contributing & Submitting WebGPU Tools
Are you authoring or researching a new WebGPU runtime, in-browser model port, or client-side neural shader? Pull requests are welcome! All submissions undergo automated validation.

---

### 🌐 Part of the @dhaulagani Developer Infrastructure & AI Suite
- ⚡ [awesome-free-developer-infra](https://github.com/dhaulagani/awesome-free-developer-infra) — Live-monitored free-tier cloud VPS, serverless DBs & developer tools.
- 🤖 [awesome-free-ai-apis](https://github.com/dhaulagani/awesome-free-ai-apis) — Free AI inference APIs, reasoning models (DeepSeek R1, Llama 3.3) & endpoints.
- 🧠 [awesome-sentient-ai](https://github.com/dhaulagani/awesome-sentient-ai) — Open-source cognitive architectures, episodic memory & world models.
- 📓 [awesome-free-cloud-notebooks](https://github.com/dhaulagani/awesome-free-cloud-notebooks) — Free cloud Jupyter notebooks, GPU servers & Colab/Kaggle alternatives.
- ⚡ [awesome-webgpu-ai](https://github.com/dhaulagani/awesome-webgpu-ai) — In-browser WebGPU runtimes, client-side LLMs & zero-server ML.
- 🎙️ [powerful-realtime-voice-ai](https://github.com/dhaulagani/powerful-realtime-voice-ai) — Full-duplex speech-to-speech (S2S) models, neural TTS & WebRTC agents.

**Maintained with ❤️ by [@dhaulagani](https://github.com/dhaulagani)** | Support open-source AI tooling via [GitHub Sponsors](https://github.com/sponsors/dhaulagani).
---
layout: publication
title: 'Chain-of-frames: Advancing Video Understanding In Multimodal Llms Via Frame-aware Reasoning'
authors: Sara Ghazanfari, Francesco Croce, Nicolas Flammarion, Prashanth Krishnamurthy, Farshad Khorrami, Siddharth Garg
conference: "Arxiv"
year: 2025
bibkey: ghazanfari2025chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00318"}
  - {name: "Code", url: "https://github.com/SaraGhazanfari/CoF}{github.com/SaraGhazanfari/CoF"}
tags: ['RAG', 'Multimodal Models', 'Has Code']
---
Recent work has shown that eliciting Large Language Models (LLMs) to generate reasoning traces in natural language before answering the user's request can significantly improve their performance across tasks. This approach has been extended to multimodal LLMs, where the models can produce chain-of-thoughts (CoT) about the content of input images and videos. In this work, we propose to obtain video LLMs whose reasoning steps are grounded in, and explicitly refer to, the relevant video frames. For this, we first create CoF-Data, a large dataset of diverse questions, answers, and corresponding frame-grounded reasoning traces about both natural and synthetic videos, spanning various topics and tasks. Then, we fine-tune existing video LLMs on this chain-of-frames (CoF) data. Our approach is simple and self-contained, and, unlike existing approaches for video CoT, does not require auxiliary networks to select or caption relevant frames. We show that our models based on CoF are able to generate chain-of-thoughts that accurately refer to the key frames to answer the given question. This, in turn, leads to improved performance across multiple video understanding benchmarks, for example, surpassing leading video LLMs on Video-MME, MVBench, and VSI-Bench, and notably reducing the hallucination rate. Code available at https://github.com/SaraGhazanfari/CoF\}\{github.com/SaraGhazanfari/CoF.

---
layout: publication
title: 'FLASH: Latent-aware Semi-autoregressive Speculative Decoding For Multimodal Tasks'
authors: Zihua Wang, Ruibo Li, Haozhe Du, Joey Tianyi Zhou, Yu Zhang, Xu Yang
conference: "Arxiv"
year: 2025
bibkey: wang2025latent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12728"}
  - {name: "Code", url: "https://github.com/ZihuaEvan/FlashSD/}{[here]"}
tags: ['Multimodal Models', 'Tools', 'Reinforcement Learning', 'Tokenization', 'RAG', 'GPT', 'Pretraining Methods', 'Has Code']
---
Large language and multimodal models (LLMs and LMMs) exhibit strong inference capabilities but are often limited by slow decoding speeds. This challenge is especially acute in LMMs, where visual inputs typically comprise more tokens with lower information density than text -- an issue exacerbated by recent trends toward finer-grained visual tokenizations to boost performance. Speculative decoding has been effective in accelerating LLM inference by using a smaller draft model to generate candidate tokens, which are then selectively verified by the target model, improving speed without sacrificing output quality. While this strategy has been extended to LMMs, existing methods largely overlook the unique properties of visual inputs and depend solely on text-based draft models. In this work, we propose \textbf\{FLASH\} (Fast Latent-Aware Semi-Autoregressive Heuristics), a speculative decoding framework designed specifically for LMMs, which leverages two key properties of multimodal data to design the draft model. First, to address redundancy in visual tokens, we propose a lightweight latent-aware token compression mechanism. Second, recognizing that visual objects often co-occur within a scene, we employ a semi-autoregressive decoding strategy to generate multiple tokens per forward pass. These innovations accelerate draft decoding while maintaining high acceptance rates, resulting in faster overall inference. Experiments show that FLASH significantly outperforms prior speculative decoding approaches in both unimodal and multimodal settings, achieving up to \textbf\{2.68\\(\times\\)\} speed-up on video captioning and \textbf\{2.55\\(\times\\)\} on visual instruction tuning tasks compared to the original LMM. Our code is available \href\{https://github.com/ZihuaEvan/FlashSD/\}\{[here]\}.

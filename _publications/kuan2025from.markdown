---
layout: publication
title: 'From Alignment To Advancement: Bootstrapping Audio-language Alignment With Synthetic Data'
authors: Chun-yi Kuan, Hung-yi Lee
conference: "Arxiv"
year: 2025
bibkey: kuan2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20166'}
tags: ['RAG', 'Multimodal Models', 'Training Techniques']
---
Audio-aware large language models (ALLMs) have recently made great strides in understanding and processing audio inputs. These models are typically adapted from text-based large language models (LLMs) through additional training on audio-related tasks. However, this adaptation process presents two major limitations. First, ALLMs often suffer from catastrophic forgetting, where important textual capabilities such as instruction-following are lost after training on audio data. In some cases, models may even hallucinate sounds that are not present in the input audio, raising concerns about their reliability. Second, achieving cross-modal alignment between audio and language typically relies on large collections of task-specific question-answer pairs for instruction tuning, making the process resource-intensive. To address these issues, we leverage the backbone LLMs from ALLMs to synthesize general-purpose caption-style alignment data. We refer to this process as bootstrapping audio-language alignment via synthetic data generation from backbone LLMs (BALSa). Building on BALSa, we introduce LISTEN (Learning to Identify Sounds Through Extended Negative Samples), a contrastive-like training method designed to improve ALLMs' ability to distinguish between present and absent sounds. We further extend BALSa to multi-audio scenarios, where the model either explains the differences between audio inputs or produces a unified caption that describes them all, thereby enhancing audio-language alignment. Experimental results indicate that our method effectively mitigates audio hallucinations while reliably maintaining strong performance in audio understanding, reasoning, and instruction-following skills. Moreover, incorporating multi-audio training further enhances the model's comprehension and reasoning capabilities. Overall, BALSa offers an efficient and scalable approach to the development of ALLMs.

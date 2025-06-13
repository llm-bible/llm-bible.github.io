---
layout: publication
title: 'Precision Where It Matters: A Novel Spike Aware Mixed-precision Quantization Strategy For Llama-based Language Models'
authors: Lucas Maisonnave, Cyril Moineau, Olivier Bichler, Fabrice Rastello
conference: "Arxiv"
year: 2025
bibkey: maisonnave2025precision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.21553"}
tags: ['Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Quantization']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
various natural language processing tasks. However, their size presents
significant challenges for deployment and inference. This paper investigates
the quantization of LLMs, focusing on the LLaMA architecture and its
derivatives. We challenge existing assumptions about activation outliers in
LLMs and propose a novel mixed-precision quantization approach tailored for
LLaMA-like models. Our method leverages the observation that activation spikes
in LLaMA architectures are predominantly concentrated in specific projection
layers. By applying higher precision (FP16 or FP8) to these layers while
quantizing the rest of the model to lower bit-widths, we achieve superior
performance compared to existing quantization techniques. Experimental results
on LLaMA2, LLaMA3, and Mistral models demonstrate significant improvements in
perplexity and zero-shot accuracy, particularly for 8-bit per-tensor
quantization. Our approach outperforms general-purpose methods designed to
handle outliers across all architecture types, highlighting the benefits of
architecture-specific quantization strategies. This research contributes to the
ongoing efforts to make LLMs more efficient and deployable, potentially
enabling their use in resource-constrained environments. Our findings emphasize
the importance of considering model-specific characteristics in developing
effective quantization pipelines for state-of-the-art language models by
identifying and targeting a small number of projections that concentrate
activation spikes.

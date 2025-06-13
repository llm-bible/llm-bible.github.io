---
layout: publication
title: 'Cdquant: Greedy Coordinate Descent For Accurate LLM Quantization'
authors: Pranav Ajit Nair, Arun Sai Suggala
conference: "Arxiv"
year: 2024
bibkey: nair2024greedy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17542"}
tags: ['Efficiency and Optimization', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Quantization']
---
Large language models (LLMs) have recently demonstrated remarkable
performance across diverse language tasks. But their deployment is often
constrained by their substantial computational and storage requirements.
Quantization has emerged as a key technique for addressing this challenge,
enabling the compression of large models with minimal impact on performance.
The recent GPTQ algorithm, a post-training quantization (PTQ) method, has
proven highly effective for compressing LLMs, sparking a wave of research that
leverages GPTQ as a core component. Recognizing the pivotal role of GPTQ in the
PTQ landscape, we introduce CDQuant, a simple and scalable alternative to GPTQ
with improved performance. CDQuant uses greedy coordinate descent to minimize
the layer-wise reconstruction loss to achieve high-quality quantized weights.
Our algorithm is easy to implement and scales efficiently to models with
hundreds of billions of parameters. We perform extensive evaluation on Gemma,
and PaLM2 model families, and demonstrate that CDQuant consistently outperforms
GPTQ in 2-4 bit weight quantization. Moreover, CDQuant improves the performance
of state-of-the-art PTQ techniques such as QuIP and FrameQuant when used as a
replacement for their GPTQ component, resulting in further gains in quality.

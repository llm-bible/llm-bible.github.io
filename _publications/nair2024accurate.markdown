---
layout: publication
title: Cdquant Accurate Post-training Weight Quantization Of Large Pre-trained Models Using Greedy Coordinate Descent
authors: Nair Pranav Ajit, Suggala Arun Sai
conference: "Arxiv"
year: 2024
bibkey: nair2024accurate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17542"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Quantization', 'RAG', 'Training Techniques']
---
Large language models (LLMs) have recently demonstrated remarkable performance across diverse language tasks. But their deployment is often constrained by their substantial computational and storage requirements. Quantization has emerged as a key technique for addressing this challenge enabling the compression of large models with minimal impact on performance. The recent GPTQ algorithm a post-training quantization (PTQ) method has proven highly effective for compressing LLMs sparking a wave of research that leverages GPTQ as a core component. Recognizing the pivotal role of GPTQ in the PTQ landscape we introduce CDQuant a simple and scalable alternative to GPTQ with improved performance. CDQuant uses coordinate descent to minimize the layer-wise reconstruction loss to achieve high-quality quantized weights. Our algorithm is easy to implement and scales efficiently to models with hundreds of billions of parameters. Through extensive evaluation on the PaLM2 model family we demonstrate that CDQuant consistently outperforms GPTQ across diverse model sizes and quantization levels. In particular for INT2 quantization of PaLM2-Otter CDQuant achieves a 1037; reduction in perplexity compared to GPTQ.

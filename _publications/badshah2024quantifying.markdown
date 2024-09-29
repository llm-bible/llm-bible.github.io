---
layout: publication
title: "Quantifying The Capabilities Of Llms Across Scale And Precision"
authors: Badshah Sher, Sajjad Hassan
conference: "Arxiv"
year: 2024
bibkey: badshah2024quantifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03146"}
tags: ['Applications', 'Efficiency And Optimization', 'Quantization']
---
Scale is often attributed as one of the factors that cause an increase in the performance of LLMs resulting in models with billion and trillion parameters. One of the limitations of such large models is the high computational requirements that limit their usage deployment and debugging in resource-constrained scenarios. Two commonly used alternatives to bypass these limitations are to use the smaller versions of LLMs (e.g. Llama 7B instead of Llama 70B) and lower the memory requirements by using quantization. While these approaches effectively address the limitation of resources their impact on model performance needs thorough examination. In this study we perform a comprehensive evaluation to investigate the effect of model scale and quantization on the performance. We experiment with two major families of open-source instruct models ranging from 7 billion to 70 billion parameters. Our extensive zero-shot experiments across various tasks including natural language understanding reasoning misinformation detection and hallucination reveal that larger models generally outperform their smaller counterparts suggesting that scale remains an important factor in enhancing performance. We found that larger models show exceptional resilience to precision reduction and can maintain high accuracy even at 4-bit quantization for numerous tasks and they serve as a better solution than using smaller models at high precision under similar memory requirements.

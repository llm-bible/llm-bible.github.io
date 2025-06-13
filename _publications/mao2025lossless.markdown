---
layout: publication
title: 'Lossless Compression Of Large Language Model-generated Text Via Next-token Prediction'
authors: Yu Mao, Holger Pirk, Chun Jason Xue
conference: "Arxiv"
year: 2025
bibkey: mao2025lossless
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.06297"}
tags: ['Security', 'Tools']
---
As large language models (LLMs) continue to be deployed and utilized across domains, the volume of LLM-generated data is growing rapidly. This trend highlights the increasing importance of effective and lossless compression for such data in modern text management systems. However, compressing LLM-generated data presents unique challenges compared to traditional human- or machine-generated content. Traditional machine-generated data is typically derived from computational processes or device outputs, often highly structured and limited to low-level elements like labels or numerical values. This structure enables conventional lossless compressors to perform efficiently. In contrast, LLM-generated data is more complex and diverse, requiring new approaches for effective compression. In this work, we conduct the first systematic investigation of lossless compression techniques tailored specifically to LLM-generated data. Notably, because LLMs are trained via next-token prediction, we find that LLM-generated data is highly predictable for the models themselves. This predictability enables LLMs to serve as efficient compressors of their own outputs. Through extensive experiments with 14 representative LLMs and 8 LLM-generated datasets from diverse domains, we show that LLM-based prediction methods achieve remarkable compression rates, exceeding 20x, far surpassing the 3x rate achieved by Gzip, a widely used general-purpose compressor. Furthermore, this advantage holds across different LLM sizes and dataset types, demonstrating the robustness and practicality of LLM-based methods in lossless text compression under generative AI workloads.

---
layout: publication
title: GPTQT\: Quantize Large Language Models Twice To Push The Efficiency
authors: Guo Yipin, Lang Yilin, Ren Qinyuan
conference: "Arxiv"
year: 2024
bibkey: guo2024quantize
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02891"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Quantization', 'RAG', 'Training Techniques']
---
Due to their large size generative Large Language Models (LLMs) require significant computing and storage resources. This paper introduces a new post-training quantization method GPTQT to reduce memory usage and enhance processing speed by expressing the weight of LLM in 3bit/2bit. Practice has shown that minimizing the quantization error of weights is ineffective leading to overfitting. Therefore GPTQT employs a progressive two-step approach initially quantizing weights using Linear quantization to a relatively high bit followed by converting obtained int weight to lower bit binary coding. A re-explore strategy is proposed to optimize initial scaling factor. During inference these steps are merged into pure binary coding enabling efficient computation. Testing across various models and datasets confirms GPTQTs effectiveness. Compared to the strong 3-bit quantization baseline GPTQT further reduces perplexity by 4.01 on opt-66B and increases speed by 1.24 times on opt-30b. The results on Llama2 show that GPTQT is currently the best binary coding quantization method for such kind of LLMs.

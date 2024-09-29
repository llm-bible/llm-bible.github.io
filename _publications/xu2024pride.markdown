---
layout: publication
title: Pride and Prejudice LLM Amplifies Self-Bias in Self-Refinement
authors: Xu Wenda, Zhu Guanglei, Zhao Xuandong, Pan Liangming, Li Lei, Wang William Yang
conference: "Arxiv"
year: 2024
bibkey: xu2024pride
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11436"}
  - {name: "Code", url: "https://github.com/xu1998hz/llm_self_bias"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Has Code', 'Language Modeling', 'Model Architecture']
---
Recent studies show that large language models (LLMs) improve their performance through self-feedback on certain tasks while degrade on others. We discovered that such a contrary is due to LLMs bias in evaluating their own output. In this paper we formally define LLMs self-bias - the tendency to favor its own generation - using two statistics. We analyze six LLMs (GPT-4 GPT-3.5 Gemini LLaMA2 Mixtral and DeepSeek) on translation constrained text generation and mathematical reasoning tasks. We find that self-bias is prevalent in all examined LLMs across multiple languages and tasks. Our analysis reveals that while the self-refine pipeline improves the fluency and understandability of model outputs it further amplifies self-bias. To mitigate such biases we discover that larger model size and external feedback with accurate assessment can significantly reduce bias in the self-refine pipeline leading to actual performance improvement in downstream tasks. The code and data are released at https://github.com/xu1998hz/llm_self_bias.

---
layout: publication
title: How Does Quantization Affect Multilingual Llms
authors: Marchisio Kelly, Dash Saurabh, Chen Hongyu, Aumiller Dennis, Üstün Ahmet, Hooker Sara, Ruder Sebastian
conference: "Arxiv"
year: 2024
bibkey: marchisio2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.03211"}
tags: ['Efficiency And Optimization', 'Prompting', 'Quantization', 'RAG']
---
Quantization techniques are widely used to improve inference speed and deployment of large language models. While a wide body of work examines the impact of quantized LLMs on English tasks none have examined the effect of quantization across languages. We conduct a thorough analysis of quantized multilingual LLMs focusing on their performance across languages and at varying scales. We use automatic benchmarks LLM-as-a-Judge methods and human evaluation finding that (1) harmful effects of quantization are apparent in human evaluation and automatic metrics severely underestimate the detriment a 1.737; average drop in Japanese across automatic tasks corresponds to a 16.037; drop reported by human evaluators on realistic prompts; (2) languages are disparately affected by quantization with non-Latin script languages impacted worst; and (3) challenging tasks such as mathematical reasoning degrade fastest. As the ability to serve low-compute models is critical for wide global adoption of NLP technologies our results urge consideration of multilingual performance as a key evaluation criterion for efficient models.

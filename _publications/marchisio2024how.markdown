---
layout: publication
title: 'How Does Quantization Affect Multilingual Llms?'
authors: Kelly Marchisio, Saurabh Dash, Hongyu Chen, Dennis Aumiller, Ahmet Üstün, Sara Hooker, Sebastian Ruder
conference: "Arxiv"
year: 2024
bibkey: marchisio2024how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.03211'}
tags: ['RAG', 'Efficiency and Optimization', 'Prompting', 'Quantization']
---
Quantization techniques are widely used to improve inference speed and
deployment of large language models. While a wide body of work examines the
impact of quantization on LLMs in English, none have evaluated across
languages. We conduct a thorough analysis of quantized multilingual LLMs,
focusing on performance across languages and at varying scales. We use
automatic benchmarks, LLM-as-a-Judge, and human evaluation, finding that (1)
harmful effects of quantization are apparent in human evaluation, which
automatic metrics severely underestimate: a 1.7% average drop in Japanese
across automatic tasks corresponds to a 16.0% drop reported by human evaluators
on realistic prompts; (2) languages are disparately affected by quantization,
with non-Latin script languages impacted worst; and (3) challenging tasks like
mathematical reasoning degrade fastest. As the ability to serve low-compute
models is critical for wide global adoption of NLP technologies, our results
urge consideration of multilingual performance as a key evaluation criterion
for efficient models.

---
layout: publication
title: 'Shakespearean Sparks: The Dance Of Hallucination And Creativity In Llms'' Decoding Layers'
authors: Zicong He, Boxuan Zhang, Lu Cheng
conference: "Arxiv"
year: 2025
bibkey: he2025shakespearean
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02851"}
  - {name: "Code", url: "https://github.com/ZicongHe2002/HCL-Spark"}
tags: ['Tools', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs) are known to hallucinate, a phenomenon often
linked to creativity. While previous research has primarily explored this
connection through theoretical or qualitative lenses, our work takes a
quantitative approach to systematically examine the relationship between
hallucination and creativity in LLMs. Given the complex nature of creativity,
we propose a narrow definition tailored to LLMs and introduce an evaluation
framework, HCL, which quantifies Hallucination and Creativity across different
Layers of LLMs during decoding. Our empirical analysis reveals a tradeoff
between hallucination and creativity that is consistent across layer depth,
model type, and model size. Notably, across different model architectures, we
identify a specific layer at each model size that optimally balances this
tradeoff. Additionally, the optimal layer tends to appear in the early layers
of larger models, and the confidence of the model is also significantly higher
at this layer. These findings provide a quantitative perspective that offers
new insights into the interplay between LLM creativity and hallucination. The
code and data for our experiments are available at
https://github.com/ZicongHe2002/HCL-Spark.

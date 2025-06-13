---
layout: publication
title: 'What Is Your Data Worth To GPT? Llm-scale Data Valuation With Influence Functions'
authors: Sang Keun Choe, Hwijeen Ahn, Juhan Bae, Kewen Zhao, Minsoo Kang, Youngseog Chung, Adithya Pratapa, Willie Neiswanger, Emma Strubell, Teruko Mitamura, Jeff Schneider, Eduard Hovy, Roger Grosse, Eric Xing
conference: "Arxiv"
year: 2024
bibkey: choe2024what
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.13954'}
tags: ['Training Techniques', 'RAG', 'Model Architecture', 'GPT']
---
Large language models (LLMs) are trained on a vast amount of human-written
data, but data providers often remain uncredited. In response to this issue,
data valuation (or data attribution), which quantifies the contribution or
value of each data to the model output, has been discussed as a potential
solution. Nevertheless, applying existing data valuation methods to recent LLMs
and their vast training datasets has been largely limited by prohibitive
compute and memory costs. In this work, we focus on influence functions, a
popular gradient-based data valuation method, and significantly improve its
scalability with an efficient gradient projection strategy called LoGra that
leverages the gradient structure in backpropagation. We then provide a
theoretical motivation of gradient projection approaches to influence functions
to promote trust in the data valuation process. Lastly, we lower the barrier to
implementing data valuation systems by introducing LogIX, a software package
that can transform existing training code into data valuation code with minimal
effort. In our data valuation experiments, LoGra achieves competitive accuracy
against more expensive baselines while showing up to 6,500x improvement in
throughput and 5x reduction in GPU memory usage when applied to
Llama3-8B-Instruct and the 1B-token dataset.

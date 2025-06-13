---
layout: publication
title: 'Can Llms Extract Frame-semantic Arguments?'
authors: Jacob Devasier, Rishabh Mediratta, Chengkai Li
conference: "Arxiv"
year: 2025
bibkey: devasier2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12516"}
tags: ['Fine-Tuning', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Frame-semantic parsing is a critical task in natural language understanding,
yet the ability of large language models (LLMs) to extract frame-semantic
arguments remains underexplored. This paper presents a comprehensive evaluation
of LLMs on frame-semantic argument identification, analyzing the impact of
input representation formats, model architectures, and generalization to unseen
and out-of-domain samples. Our experiments, spanning models from 0.5B to 78B
parameters, reveal that JSON-based representations significantly enhance
performance, and while larger models generally perform better, smaller models
can achieve competitive results through fine-tuning. We also introduce a novel
approach to frame identification leveraging predicted frame elements, achieving
state-of-the-art performance on ambiguous targets. Despite strong
generalization capabilities, our analysis finds that LLMs still struggle with
out-of-domain data.

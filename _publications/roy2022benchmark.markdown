---
layout: publication
title: 'Benchclamp: A Benchmark For Evaluating Language Models On Syntactic And Semantic Parsing'
authors: Subhro Roy, Sam Thomson, Tongfei Chen, Richard Shin, Adam Pauls, Jason Eisner, Benjamin Van Durme
conference: "Arxiv"
year: 2022
bibkey: roy2022benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.10668"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Recent work has shown that generation from a prompted or fine-tuned language
model can perform well at semantic parsing when the output is constrained to be
a valid semantic representation. We introduce BenchCLAMP, a Benchmark to
evaluate Constrained LAnguage Model Parsing, that includes context-free
grammars for seven semantic parsing datasets and two syntactic parsing datasets
with varied output representations, as well as a constrained decoding interface
to generate only valid outputs covered by these grammars. We provide low,
medium, and high resource splits for each dataset, allowing accurate comparison
of various language models under different data regimes. Our benchmark supports
evaluation of language models using prompt-based learning as well as
fine-tuning. We benchmark eight language models, including two GPT-3 variants
available only through an API. Our experiments show that encoder-decoder
pretrained language models can achieve similar performance or surpass
state-of-the-art methods for syntactic and semantic parsing when the model
output is constrained to be valid.

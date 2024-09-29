---
layout: publication
title: Benchclamp A Benchmark For Evaluating Language Models On Syntactic And Semantic Parsing
authors: Roy Subhro, Thomson Sam, Chen Tongfei, Shin Richard, Pauls Adam, Eisner Jason, Van Durme Benjamin
conference: "Arxiv"
year: 2022
bibkey: roy2022benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.10668"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Recent work has shown that generation from a prompted or fine45;tuned language model can perform well at semantic parsing when the output is constrained to be a valid semantic representation. We introduce BenchCLAMP a Benchmark to evaluate Constrained LAnguage Model Parsing that includes context45;free grammars for seven semantic parsing datasets and two syntactic parsing datasets with varied output representations as well as a constrained decoding interface to generate only valid outputs covered by these grammars. We provide low medium and high resource splits for each dataset allowing accurate comparison of various language models under different data regimes. Our benchmark supports evaluation of language models using prompt45;based learning as well as fine45;tuning. We benchmark eight language models including two GPT45;3 variants available only through an API. Our experiments show that encoder45;decoder pretrained language models can achieve similar performance or surpass state45;of45;the45;art methods for syntactic and semantic parsing when the model output is constrained to be valid.

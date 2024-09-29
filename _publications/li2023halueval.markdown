---
layout: publication
title: Halueval A Large-scale Hallucination Evaluation Benchmark For Large Language Models
authors: Li Junyi, Cheng Xiaoxue, Zhao Wayne Xin, Nie Jian-yun, Wen Ji-rong
conference: "Arxiv"
year: 2023
bibkey: li2023halueval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11747"}
  - {name: "Code", url: "https://github.com/RUCAIBox/HaluEval"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools']
---
Large language models (LLMs) such as ChatGPT are prone to generate hallucinations i.e. content that conflicts with the source or cannot be verified by the factual knowledge. To understand what types of content and to which extent LLMs are apt to hallucinate we introduce the Hallucination Evaluation benchmark for Large Language Models (HaluEval) a large collection of generated and human-annotated hallucinated samples for evaluating the performance of LLMs in recognizing hallucination. To generate these samples we propose a ChatGPT-based two-step framework i.e. sampling-then-filtering. Besides we also hire some human labelers to annotate the hallucinations in ChatGPT responses. The empirical results suggest that ChatGPT is likely to generate hallucinated content in specific topics by fabricating unverifiable information (i.e. about 19.537; responses). Moreover existing LLMs face great challenges in recognizing the hallucinations in texts. However our experiments also prove that providing external knowledge or adding reasoning steps can help LLMs recognize hallucinations. Our benchmark can be accessed at https://github.com/RUCAIBox/HaluEval.

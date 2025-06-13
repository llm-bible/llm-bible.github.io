---
layout: publication
title: 'Self-training Large Language Models For Tool-use Without Demonstrations'
authors: Ne Luo, Aryo Pradipta Gema, Xuanli He, Emile Van Krieken, Pietro Lesci, Pasquale Minervini
conference: "Arxiv"
year: 2025
bibkey: luo2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05867"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large language models (LLMs) remain prone to factual inaccuracies and
computational errors, including hallucinations and mistakes in mathematical
reasoning. Recent work augmented LLMs with tools to mitigate these
shortcomings, but often requires curated gold tool-use demonstrations. In this
paper, we investigate whether LLMs can learn to use tools without
demonstrations. First, we analyse zero-shot prompting strategies to guide LLMs
in tool utilisation. Second, we propose a self-training method to synthesise
tool-use traces using the LLM itself. We compare supervised fine-tuning and
preference fine-tuning techniques for fine-tuning the model on datasets
constructed using existing Question Answering (QA) datasets, i.e., TriviaQA and
GSM8K. Experiments show that tool-use enhances performance on a long-tail
knowledge task: 3.7% on PopQA, which is used solely for evaluation, but leads
to mixed results on other datasets, i.e., TriviaQA, GSM8K, and NQ-Open. Our
findings highlight the potential and challenges of integrating external tools
into LLMs without demonstrations.

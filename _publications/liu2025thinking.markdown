---
layout: publication
title: 'On The Thinking-language Modeling Gap In Large Language Models'
authors: Chenxi Liu, Yongqiang Chen, Tongliang Liu, James Cheng, Bo Han, Kun Zhang
conference: "Arxiv"
year: 2025
bibkey: liu2025thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12896"}
tags: ['Language Modeling', 'Prompting', 'Ethics and Bias']
---
System 2 reasoning is one of the defining characteristics of intelligence, which requires slow and logical thinking. Human conducts System 2 reasoning via the language of thoughts that organizes the reasoning process as a causal sequence of mental language, or thoughts. Recently, it has been observed that System 2 reasoning can be elicited from Large Language Models (LLMs) pre-trained on large-scale natural languages. However, in this work, we show that there is a significant gap between the modeling of languages and thoughts. As language is primarily a tool for humans to share knowledge and thinking, modeling human language can easily absorb language biases into LLMs deviated from the chain of thoughts in minds. Furthermore, we show that the biases will mislead the eliciting of "thoughts" in LLMs to focus only on a biased part of the premise. To this end, we propose a new prompt technique termed Language-of-Thoughts (LoT) to demonstrate and alleviate this gap. Instead of directly eliciting the chain of thoughts from partial information, LoT instructs LLMs to adjust the order and token used for the expressions of all the relevant information. We show that the simple strategy significantly reduces the language modeling biases in LLMs and improves the performance of LLMs across a variety of reasoning tasks.

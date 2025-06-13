---
layout: publication
title: 'Mm-eval: A Hierarchical Benchmark For Modern Mongolian Evaluation In Llms'
authors: Mengyuan Zhang, Ruihui Wang, Bo Xia, Yuan Sun, Xiaobing Zhao
conference: "Arxiv"
year: 2024
bibkey: zhang2024mm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.09492'}
  - {name: "Code", url: 'https://github.com/joenahm/MM-Eval'}
tags: ['GPT', 'Has Code', 'Model Architecture']
---
Large language models (LLMs) excel in high-resource languages but face
notable challenges in low-resource languages like Mongolian. This paper
addresses these challenges by categorizing capabilities into language abilities
(syntax and semantics) and cognitive abilities (knowledge and reasoning). To
systematically evaluate these areas, we developed MM-Eval, a specialized
dataset based on Modern Mongolian Language Textbook I and enriched with WebQSP
and MGSM datasets.
  Preliminary experiments on models including Qwen2-7B-Instruct, GLM4-9b-chat,
Llama3.1-8B-Instruct, GPT-4, and DeepseekV2.5 revealed that: 1) all models
performed better on syntactic tasks than semantic tasks, highlighting a gap in
deeper language understanding; and 2) knowledge tasks showed a moderate
decline, suggesting that models can transfer general knowledge from
high-resource to low-resource contexts.
  The release of MM-Eval, comprising 569 syntax, 677 semantics, 344 knowledge,
and 250 reasoning tasks, offers valuable insights for advancing NLP and LLMs in
low-resource languages like Mongolian. The dataset is available at
https://github.com/joenahm/MM-Eval.

---
layout: publication
title: 'Demonstration Notebook: Finding The Most Suited In-context Learning Example From Interactions'
authors: Yiming Tang, Bin Dong
conference: "Arxiv"
year: 2024
bibkey: tang2024demonstration
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10878"}
tags: ['Fine-Tuning', 'Applications', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) benefit greatly from prompt engineering, with
in-context learning standing as a pivital technique. While former approaches
have provided various ways to construct the demonstrations used for in-context
learning, they often ignore the inherent heterogeneity within datasets,
applying the same demonstrations to all reasoning questions. We observed that
the effectiveness of demonstrations varies depending on the specific question.
This motivates our exploration of using prompt engineering to select
appropriate demonstrations. To address the challenge of automatically creating
and choosing demonstrations tailored to each question, we propose a novel
prompt engineering workflow built around a novel object called the
"demonstration notebook." This notebook helps identify the most suitable
in-context learning example for a question by gathering and reusing information
from the LLM's past interactions. Our experiments show that this approach
outperforms all existing methods for automatic demonstration construction and
selection (as far as we know), achieving state-of-the-art results on serveral
reasoning benchmarks. The method's versatility is further demonstrated by its
success in text summarization and prompt compression tasks. Additionally, we
contribute a rigorous analysis method to reveal the "demonstrative regime" of a
demonstration, providing valuable insights into how demonstrations relate to
different question types within a dataset.

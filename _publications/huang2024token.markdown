---
layout: publication
title: 'Toblend: Token-level Blending With An Ensemble Of Llms To Attack Ai-generated Text Detection'
authors: Fan Huang, Haewoon Kwak, Jisun An
conference: "Arxiv"
year: 2024
bibkey: huang2024token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11167"}
tags: ['Language Modeling', 'Security', 'Applications']
---
The robustness of AI-content detection models against sophisticated
adversarial strategies, such as paraphrasing or word switching, is a rising
concern in natural language generation (NLG) applications. This study proposes
ToBlend, a novel token-level ensemble text generation method to challenge the
robustness of current AI-content detection approaches by utilizing multiple
sets of candidate generative large language models (LLMs). By randomly sampling
token(s) from candidate LLMs sets, we find ToBlend significantly drops the
performance of most mainstream AI-content detection methods. We evaluate the
text quality produced under different ToBlend settings based on annotations
from experienced human experts. We proposed a fine-tuned Llama3.1 model to
distinguish the ToBlend generated text more accurately. Our findings underscore
our proposed text generation approach's great potential in deceiving and
improving detection models. Our datasets, codes, and annotations are
open-sourced.

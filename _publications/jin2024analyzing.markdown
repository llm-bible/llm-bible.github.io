---
layout: publication
title: 'Analyzing The Role Of Semantic Representations In The Era Of Large Language Models'
authors: Zhijing Jin, Yuen Chen, Fernando Gonzalez, Jiarui Liu, Jiayi Zhang, Julian Michael, Bernhard Schölkopf, Mona Diab
conference: "Arxiv"
year: 2024
bibkey: jin2024analyzing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.01502'}
  - {name: "Code", url: 'https://github.com/causalNLP/amr_llm'}
tags: ['Prompting', 'Has Code']
---
Traditionally, natural language processing (NLP) models often use a rich set
of features created by linguistic expertise, such as semantic representations.
However, in the era of large language models (LLMs), more and more tasks are
turned into generic, end-to-end sequence generation problems. In this paper, we
investigate the question: what is the role of semantic representations in the
era of LLMs? Specifically, we investigate the effect of Abstract Meaning
Representation (AMR) across five diverse NLP tasks. We propose an AMR-driven
chain-of-thought prompting method, which we call AMRCoT, and find that it
generally hurts performance more than it helps. To investigate what AMR may
have to offer on these tasks, we conduct a series of analysis experiments. We
find that it is difficult to predict which input examples AMR may help or hurt
on, but errors tend to arise with multi-word expressions, named entities, and
in the final inference step where the LLM must connect its reasoning over the
AMR to its prediction. We recommend focusing on these areas for future work in
semantic representations for LLMs. Our code:
https://github.com/causalNLP/amr_llm.

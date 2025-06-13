---
layout: publication
title: 'Do Large Language Models Know Who Did What To Whom?'
authors: Joseph M. Denning, Xiaohan Hannah Guo, Bryor Snefjella, Idan A. Blank
conference: "Arxiv"
year: 2025
bibkey: denning2025do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16884"}
tags: ['Training Techniques', 'Agentic', 'Attention Mechanism', 'Model Architecture']
---
Large Language Models (LLMs) are commonly criticized for not understanding
language. However, many critiques focus on cognitive abilities that, in humans,
are distinct from language processing. Here, we instead study a kind of
understanding tightly linked to language: inferring who did what to whom
(thematic roles) in a sentence. Does the central training objective of
LLMs-word prediction-result in sentence representations that capture thematic
roles? In two experiments, we characterized sentence representations in four
LLMs. In contrast to human similarity judgments, in LLMs the overall
representational similarity of sentence pairs reflected syntactic similarity
but not whether their agent and patient assignments were identical vs.
reversed. Furthermore, we found little evidence that thematic role information
was available in any subset of hidden units. However, some attention heads
robustly captured thematic roles, independently of syntax. Therefore, LLMs can
extract thematic roles but, relative to humans, this information influences
their representations more weakly.

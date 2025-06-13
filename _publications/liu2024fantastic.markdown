---
layout: publication
title: 'Fantastic Semantics And Where To Find Them: Investigating Which Layers Of Generative Llms Reflect Lexical Semantics'
authors: Zhu Liu, Cunliang Kong, Ying Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: liu2024fantastic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01509"}
  - {name: "Code", url: "https://github.com/RyanLiut/LLM_LexSem"}
tags: ['Model Architecture', 'Language Modeling', 'Reinforcement Learning', 'Has Code', 'BERT', 'Prompting']
---
Large language models have achieved remarkable success in general language
understanding tasks. However, as a family of generative methods with the
objective of next token prediction, the semantic evolution with the depth of
these models are not fully explored, unlike their predecessors, such as
BERT-like architectures. In this paper, we specifically investigate the
bottom-up evolution of lexical semantics for a popular LLM, namely Llama2, by
probing its hidden states at the end of each layer using a contextualized word
identification task. Our experiments show that the representations in lower
layers encode lexical semantics, while the higher layers, with weaker semantic
induction, are responsible for prediction. This is in contrast to models with
discriminative objectives, such as mask language modeling, where the higher
layers obtain better lexical semantics. The conclusion is further supported by
the monotonic increase in performance via the hidden states for the last
meaningless symbols, such as punctuation, in the prompting strategy. Our codes
are available at https://github.com/RyanLiut/LLM_LexSem.

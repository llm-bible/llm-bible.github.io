---
layout: publication
title: Evaluating Transformers Ability to Learn Mildly Context-Sensitive Languages
authors: Wang Shunjie, Steinert-threlkeld Shane
conference: "Arxiv"
year: 2023
bibkey: wang2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.00857"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Despite the fact that Transformers perform well in NLP tasks recent studies suggest that self-attention is theoretically limited in learning even some regular and context-free languages. These findings motivated us to think about their implications in modeling natural language which is hypothesized to be mildly context-sensitive. We test the Transformers ability to learn mildly context-sensitive languages of varying complexities and find that they generalize well to unseen in-distribution data but their ability to extrapolate to longer strings is worse than that of LSTMs. Our analyses show that the learned self-attention patterns and representations modeled dependency relations and demonstrated counting behavior which may have helped the models solve the languages.

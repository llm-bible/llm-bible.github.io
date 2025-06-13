---
layout: publication
title: 'Counterfactual Reasoning: Do Language Models Need World Knowledge For Causal Understanding?'
authors: Jiaxuan Li, Lang Yu, Allyson Ettinger
conference: "Arxiv"
year: 2022
bibkey: li2022counterfactual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.03278"}
tags: ['RAG', 'Model Architecture', 'GPT', 'Reinforcement Learning']
---
Current pre-trained language models have enabled remarkable improvements in
downstream tasks, but it remains difficult to distinguish effects of
statistical correlation from more systematic logical reasoning grounded on
understanding of the real world. In this paper we tease these factors apart by
leveraging counterfactual conditionals, which force language models to predict
unusual consequences based on hypothetical propositions. We introduce a set of
tests drawn from psycholinguistic experiments, as well as larger-scale
controlled datasets, to probe counterfactual predictions from a variety of
popular pre-trained language models. We find that models are consistently able
to override real-world knowledge in counterfactual scenarios, and that this
effect is more robust in case of stronger baseline world knowledge -- however,
we also find that for most models this effect appears largely to be driven by
simple lexical cues. When we mitigate effects of both world knowledge and
lexical cues to test knowledge of linguistic nuances of counterfactuals, we
find that only GPT-3 shows sensitivity to these nuances, though this
sensitivity is also non-trivially impacted by lexical associative factors.

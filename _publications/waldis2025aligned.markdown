---
layout: publication
title: 'Aligned Probing: Relating Toxic Behavior And Model Internals'
authors: Andreas Waldis, Vagrant Gautam, Anne Lauscher, Dietrich Klakow, Iryna Gurevych
conference: "Arxiv"
year: 2025
bibkey: waldis2025aligned
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.13390"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Tools', 'Interpretability and Explainability', 'Reinforcement Learning', 'Training Techniques', 'Quantization', 'Prompting']
---
We introduce aligned probing, a novel interpretability framework that aligns
the behavior of language models (LMs), based on their outputs, and their
internal representations (internals). Using this framework, we examine over 20
OLMo, Llama, and Mistral models, bridging behavioral and internal perspectives
for toxicity for the first time. Our results show that LMs strongly encode
information about the toxicity level of inputs and subsequent outputs,
particularly in lower layers. Focusing on how unique LMs differ offers both
correlative and causal evidence that they generate less toxic output when
strongly encoding information about the input toxicity. We also highlight the
heterogeneity of toxicity, as model behavior and internals vary across unique
attributes such as Threat. Finally, four case studies analyzing detoxification,
multi-prompt evaluations, model quantization, and pre-training dynamics
underline the practical impact of aligned probing with further concrete
insights. Our findings contribute to a more holistic understanding of LMs, both
within and beyond the context of toxicity.

---
layout: publication
title: 'Mechanistic Understanding And Mitigation Of Language Confusion In English-centric Large Language Models'
authors: Ercong Nie, Helmut Schmid, Hinrich Schütze
conference: "Arxiv"
year: 2025
bibkey: nie2025mechanistic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16538'}
tags: ['Language Modeling', 'Interpretability and Explainability', 'Merging']
---
Language confusion -- where large language models (LLMs) generate unintended languages against the user's need -- remains a critical challenge, especially for English-centric models. We present the first mechanistic interpretability (MI) study of language confusion, combining behavioral benchmarking with neuron-level analysis. Using the Language Confusion Benchmark (LCB), we show that confusion points (CPs) -- specific positions where language switches occur -- are central to this phenomenon. Through layer-wise analysis with TunedLens and targeted neuron attribution, we reveal that transition failures in the final layers drive confusion. We further demonstrate that editing a small set of critical neurons, identified via comparative analysis with multilingual-tuned models, substantially mitigates confusion without harming general competence or fluency. Our approach matches multilingual alignment in confusion reduction for most languages and yields cleaner, higher-quality outputs. These findings provide new insights into the internal dynamics of LLMs and highlight neuron-level interventions as a promising direction for robust, interpretable multilingual language modeling.

---
layout: publication
title: Scaling laws for language encoding models in fMRI
authors: Antonello Richard, Vaidya Aditya, Huth Alexander G.
conference: "Arxiv"
year: 2023
bibkey: antonello2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11863"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'GPT', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques', 'Transformer']
---
Representations from transformer-based unidirectional language models are known to be effective at predicting brain responses to natural language. However most studies comparing language models to brains have used GPT-2 or similarly sized language models. Here we tested whether larger open-source models such as those from the OPT and LLaMA families are better at predicting brain responses recorded using fMRI. Mirroring scaling results from other contexts we found that brain prediction performance scales logarithmically with model size from 125M to 30B parameter models with ~15 increased encoding performance as measured by correlation with a held-out test set across 3 subjects. Similar logarithmic behavior was observed when scaling the size of the fMRI training set. We also characterized scaling for acoustic encoding models that use HuBERT WavLM and Whisper and we found comparable improvements with model size. A noise ceiling analysis of these large high-performance encoding models showed that performance is nearing the theoretical maximum for brain areas such as the precuneus and higher auditory cortex. These results suggest that increasing scale in both models and data will yield incredibly effective models of language processing in the brain enabling better scientific understanding as well as applications such as decoding.

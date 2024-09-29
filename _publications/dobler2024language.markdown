---
layout: publication
title: 'Language Adaptation On A Tight Academic Compute Budget: Tokenizer Swapping Works And Pure Bfloat16 Is Enough'
authors: Dobler Konstantin, De Melo Gerard
conference: "Arxiv"
year: 2024
bibkey: dobler2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.15793"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Tokenization', 'Training Techniques']
---
We investigate continued pretraining of LLMs for language adaptation on a tight academic budget a setting in which only a few GPUs can be used in parallel for a heavily constrained duration. We focus on adapting Mistral-7B to German or Arabic and evaluate several techniques to improve efficiency and effectiveness in this setting. Our German models adapted on this tight compute budget underperform compared to the base Mistral-7B while our Arabic models outperform several baselines showing that for sufficiently well-represented languages continued pretraining for specialization is not always helpful. Our main findings focus on training precision and tokenizer swapping. Our results show that pure bfloat16 training is a viable alternative to mixed-precision training while being much faster when only using a few GPUs. Swapping the tokenizer for a specialized one yields more efficient tokenization and is competitive with the original tokenizer which already contains some German tokens but did not significantly increase performance for German. Code and model weights are available at on GitHub.

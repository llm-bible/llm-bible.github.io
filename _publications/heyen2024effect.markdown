---
layout: publication
title: The Effect of Model Size on LLM Post-hoc Explainability via LIME
authors: Heyen Henning, Widdicombe Amy, Siegel Noah Y., Perez-ortiz Maria, Treleaven Philip
conference: "Arxiv"
year: 2024
bibkey: heyen2024effect
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05348"}
tags: ['BERT', 'Interpretability And Explainability', 'Model Architecture']
---
Large language models (LLMs) are becoming bigger to boost performance. However little is known about how explainability is affected by this trend. This work explores LIME explanations for DeBERTaV3 models of four different sizes on natural language inference (NLI) and zero-shot classification (ZSC) tasks. We evaluate the explanations based on their faithfulness to the models internal decision processes and their plausibility i.e. their agreement with human explanations. The key finding is that increased model size does not correlate with plausibility despite improved model performance suggesting a misalignment between the LIME explanations and the models internal processes as model size increases. Our results further suggest limitations regarding faithfulness metrics in NLI contexts.

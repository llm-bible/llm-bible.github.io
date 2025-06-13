---
layout: publication
title: 'Seval-ex: A Statement-level Framework For Explainable Summarization Evaluation'
authors: Tanguy Herserant, Vincent Guigue
conference: "Arxiv"
year: 2025
bibkey: herserant2025seval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.02235'}
tags: ['Interpretability and Explainability', 'Security', 'GPT', 'Model Architecture', 'Tools', 'Applications', 'Interpretability']
---
Evaluating text summarization quality remains a critical challenge in Natural
Language Processing. Current approaches face a trade-off between performance
and interpretability. We present SEval-Ex, a framework that bridges this gap by
decomposing summarization evaluation into atomic statements, enabling both high
performance and explainability. SEval-Ex employs a two-stage pipeline: first
extracting atomic statements from text source and summary using LLM, then a
matching between generated statements. Unlike existing approaches that provide
only summary-level scores, our method generates detailed evidence for its
decisions through statement-level alignments. Experiments on the SummEval
benchmark demonstrate that SEval-Ex achieves state-of-the-art performance with
0.580 correlation on consistency with human consistency judgments, surpassing
GPT-4 based evaluators (0.521) while maintaining interpretability. Finally, our
framework shows robustness against hallucination.

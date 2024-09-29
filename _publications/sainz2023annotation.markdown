---
layout: publication
title: Gollie: Annotation Guidelines Improve Zero-shot Information-extraction
authors: Sainz Oscar, García-ferrero Iker, Agerri Rodrigo, De Lacalle Oier Lopez, Rigau German, Agirre Eneko
conference: "Arxiv"
year: 2023
bibkey: sainz2023annotation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03668"}
tags: ['Pretraining Methods', 'RAG']
---
Large Language Models (LLMs) combined with instruction tuning have made significant progress when generalizing to unseen tasks. However they have been less successful in Information Extraction (IE) lagging behind task-specific models. Typically IE tasks are characterized by complex annotation guidelines that describe the task and give examples to humans. Previous attempts to leverage such information have failed even with the largest models as they are not able to follow the guidelines out of the box. In this paper we propose GoLLIE (Guideline-following Large Language Model for IE) a model able to improve zero-shot results on unseen IE tasks by virtue of being fine-tuned to comply with annotation guidelines. Comprehensive evaluation empirically demonstrates that GoLLIE is able to generalize to and follow unseen guidelines outperforming previous attempts at zero-shot information extraction. The ablation study shows that detailed guidelines are key for good results.

---
layout: publication
title: 'Leveraging Zero-shot Prompting For Efficient Language Model Distillation'
authors: Lukas Vöge, Vincent Gurgul, Stefan Lessmann
conference: "Arxiv"
year: 2024
bibkey: vöge2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15886"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Interpretability and Explainability', 'RAG', 'Training Techniques', 'Few-Shot', 'Prompting', 'Distillation']
---
This paper introduces a novel approach for efficiently distilling LLMs into
smaller, application-specific models, significantly reducing operational costs
and manual labor. Addressing the challenge of deploying computationally
intensive LLMs in specific applications or edge devices, this technique
utilizes LLMs' reasoning capabilities to generate labels and natural language
rationales for unlabeled data. Our approach enhances both finetuning and
distillation by employing a multi-task training framework where student models
mimic these rationales alongside teacher predictions. Key contributions include
the employment of zero-shot prompting to elicit teacher model rationales,
reducing the necessity for handcrafted few-shot examples and lowering the
overall token count required, which directly translates to cost savings given
the pay-per-token billing model of major tech companies' LLM APIs.
Additionally, the paper investigates the impact of explanation properties on
distillation efficiency, demonstrating that minimal performance loss occurs
even when rationale augmentation is not applied across the entire dataset,
facilitating further reductions of tokens. This research marks a step toward
the efficient training of task-specific models with minimal human intervention,
offering substantial cost-savings while maintaining, or even enhancing,
performance.

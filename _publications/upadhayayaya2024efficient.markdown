---
layout: publication
title: 'Efficient LLM Context Distillation'
authors: Rajesh Upadhayayaya, Manish Raj Osti, Zachary Smith, Chritopher Kottmyer
conference: "Arxiv"
year: 2024
bibkey: upadhayayaya2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.01930"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Few-Shot', 'RAG', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Large Language Models (LLMs) demonstrate proficiency across diverse tasks but often require targeted adaptations for specific applications. Various methods have been proposed to facilitate this adaptation, including fewshot fine-tuning, in-context learning, and context distillation. This paper specifically investigates context distillation a method that extends the utility of task-specific examples by internalizing them, thus augmenting the example set accessible for model inference. We conduct a comparative analysis of context distillation with in-context learning (ICL) and few-shot fine-tuning (FT), aiming to ascertain the efficacy of context distillation in adapting models using minimal in-context examples. Employing matched datasets from Mobach, our experiments leverage OPT models of various sizes. The results indicate that context distillation effectively adapts models, with student models attaining comparable in-domain and out-of-domain accuracies to in-context learning. Although context distillation surpasses ICL in out-of-domain generalization, it does not achieve the performance levels of FT. However, the reduced dataset size and computational demands position context distillation as a viable alternative, especially for smaller datasets. Overall, this study presents context distillation as an efficient and potent method for customizing LLMs to specific tasks.

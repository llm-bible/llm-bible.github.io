---
layout: publication
title: 'Can Llms Predict Citation Intent? An Experimental Analysis Of In-context Learning And Fine-tuning On Open Llms'
authors: Paris Koloveas, Serafeim Chatzopoulos, Thanasis Vergoulis, Christos Tryfonopoulos
conference: "Arxiv"
year: 2025
bibkey: koloveas2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14561'}
tags: ['ACL', 'Training Techniques', 'Model Architecture', 'Tools', 'Fine-Tuning', 'BERT', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
This work investigates the ability of open Large Language Models (LLMs) to predict citation intent through in-context learning and fine-tuning. Unlike traditional approaches relying on domain-specific pre-trained models like SciBERT, we demonstrate that general-purpose LLMs can be adapted to this task with minimal task-specific data. We evaluate twelve model variations across five prominent open LLM families using zero-, one-, few-, and many-shot prompting. Our experimental study identifies the top-performing model and prompting parameters through extensive in-context learning experiments. We then demonstrate the significant impact of task-specific adaptation by fine-tuning this model, achieving a relative F1-score improvement of 8% on the SciCite dataset and 4.3% on the ACL-ARC dataset compared to the instruction-tuned baseline. These findings provide valuable insights for model selection and prompt engineering. Additionally, we make our end-to-end evaluation framework and models openly available for future use.

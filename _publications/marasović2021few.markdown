---
layout: publication
title: "Few-shot Self-rationalization With Natural Language Prompts"
authors: Marasović Ana, Beltagy Iz, Downey Doug, Peters Matthew E.
conference: "Arxiv"
year: 2021
bibkey: marasović2021few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.08284"}
tags: ['Ethics And Bias', 'Few Shot', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Self-rationalization models that predict task labels and generate free-text elaborations for their predictions could enable more intuitive interaction with NLP systems. These models are however currently trained with a large amount of human-written free-text explanations for each task which hinders their broader usage. We propose to study a more realistic setting of self-rationalization using few training examples. We present FEB -- a standardized collection of four existing English-language datasets and associated metrics. We identify the right prompting approach by extensively exploring natural language prompts on FEB. Then by using this prompt and scaling the model size we demonstrate that making progress on few-shot self-rationalization is possible. We show there is still ample room for improvement in this task the average plausibility of generated explanations assessed by human annotators is at most 5137; (with GPT-3) while plausibility of human explanations is 7637;. We hope that FEB and our proposed approach will spur the community to take on the few-shot self-rationalization challenge.

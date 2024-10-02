---
layout: publication
title: 'Robust Infidelity: When Faithfulness Measures On Masked Language Models Are Misleading'
authors: Crothers Evan, Viktor Herna, Japkowicz Nathalie
conference: "Arxiv"
year: 2023
bibkey: crothers2023robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.06795"}
tags: ['BERT', 'Interpretability And Explainability', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Transformer']
---
A common approach to quantifying neural text classifier interpretability is to calculate faithfulness metrics based on iteratively masking salient input tokens and measuring changes in the model prediction. We propose that this property is better described as sensitivity to iterative masking, and highlight pitfalls in using this measure for comparing text classifier interpretability. We show that iterative masking produces large variation in faithfulness scores between otherwise comparable Transformer encoder text classifiers. We then demonstrate that iteratively masked samples produce embeddings outside the distribution seen during training, resulting in unpredictable behaviour. We further explore task-specific considerations that undermine principled comparison of interpretability using iterative masking, such as an underlying similarity to salience-based adversarial attacks. Our findings give insight into how these behaviours affect neural text classifiers, and provide guidance on how sensitivity to iterative masking should be interpreted.

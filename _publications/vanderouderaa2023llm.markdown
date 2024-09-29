---
layout: publication
title: The LLM Surgeon
authors: Van Der Ouderaa Tycho F. A., Nagel Markus, Van Baalen Mart, Asano Yuki M., Blankevoort Tijmen
conference: "Arxiv"
year: 2023
bibkey: vanderouderaa2023llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.17244"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Tools', 'Training Techniques', 'Transformer']
---
State45;of45;the45;art language models are becoming increasingly large in an effort to achieve the highest performance on large corpora of available textual data. However the sheer size of the Transformer architectures makes it difficult to deploy models within computational environmental or device45;specific constraints. We explore data45;driven compression of existing pretrained models as an alternative to training smaller models from scratch. To do so we scale Kronecker45;factored curvature approximations of the target loss landscape to large language models. In doing so we can compute both the dynamic allocation of structures that can be removed as well as updates of remaining weights that account for the removal. We provide a general framework for unstructured semi45;structured and structured pruning and improve upon weight updates to capture more correlations between weights while remaining computationally efficient. Experimentally our method can prune rows and columns from a range of OPT models and Llamav245;7B by 2037;45;3037; with a negligible loss in performance and achieve state45;of45;the45;art results in unstructured and semi45;structured pruning of large language models.

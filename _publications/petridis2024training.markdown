---
layout: publication
title: Constitutionalexperts Training A Mixture Of Principle-based Prompts
authors: Petridis Savvas, Wedin Ben, Yuan Ann, Wexler James, Thain Nithum
conference: "Arxiv"
year: 2024
bibkey: petridis2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04894"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) are highly capable at a variety of tasks given the right prompt but writing one is still a difficult and tedious process. In this work we introduce ConstitutionalExperts a method for learning a prompt consisting of constitutional principles (i.e. rules) given a training dataset. Unlike prior methods that optimize the prompt as a single entity our method incrementally improves the prompt by surgically editing individual principles. We also show that we can improve overall performance by learning unique prompts for different semantic regions of the training data and using a mixture-of-experts (MoE) architecture to route inputs at inference time. We compare our method to other state of the art prompt-optimization techniques across six benchmark datasets. We also investigate whether MoE improves these other techniques. Our results suggest that ConstitutionalExperts outperforms other prompt optimization techniques by 10.937; (F1) and that mixture-of-experts improves all techniques suggesting its broad applicability.

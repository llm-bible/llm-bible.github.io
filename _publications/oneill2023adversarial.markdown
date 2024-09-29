---
layout: publication
title: Adversarial Fine-Tuning of Language Models An Iterative Optimisation Approach for the Generation and Detection of Problematic Content
authors: O'neill Charles, Miller Jack, Ciuca Ioana, Ting Yuan-sen, Bui Thang
conference: "Arxiv"
year: 2023
bibkey: oneill2023adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.13768"}
tags: ['Fine Tuning', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Security', 'Training Techniques']
---
In this paper we tackle the emerging challenge of unintended harmful content generation in Large Language Models (LLMs) with a novel dual-stage optimisation technique using adversarial fine-tuning. Our two-pronged approach employs an adversarial model fine-tuned to generate potentially harmful prompts and a judge model iteratively optimised to discern these prompts. In this adversarial cycle the two models seek to outperform each other in the prompting phase generating a dataset of rich examples which are then used for fine-tuning. This iterative application of prompting and fine-tuning allows continuous refinement and improved performance. The performance of our approach is evaluated through classification accuracy on a dataset consisting of problematic prompts not detected by GPT-4 as well as a selection of contentious but unproblematic prompts. We show considerable increase in classification accuracy of the judge model on this challenging dataset as it undergoes the optimisation process. Furthermore we show that a rudimentary model textttada can achieve 13 higher accuracy on the hold-out test set than GPT-4 after only a few rounds of this process and that this fine-tuning improves performance in parallel tasks such as toxic comment identification.

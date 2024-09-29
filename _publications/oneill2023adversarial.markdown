---
layout: publication
title: Adversarial Fine45;tuning Of Language Models An Iterative Optimisation Approach For The Generation And Detection Of Problematic Content
authors: O'neill Charles, Miller Jack, Ciuca Ioana, Ting Yuan-sen, Bui Thang
conference: "Arxiv"
year: 2023
bibkey: oneill2023adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.13768"}
tags: ['Applications', 'GPT', 'Merging', 'Model Architecture', 'Prompting', 'Security']
---
In this paper we tackle the emerging challenge of unintended harmful content generation in Large Language Models (LLMs) with a novel dual45;stage optimisation technique using adversarial fine45;tuning. Our two45;pronged approach employs an adversarial model fine45;tuned to generate potentially harmful prompts and a judge model iteratively optimised to discern these prompts. In this adversarial cycle the two models seek to outperform each other in the prompting phase generating a dataset of rich examples which are then used for fine45;tuning. This iterative application of prompting and fine45;tuning allows continuous refinement and improved performance. The performance of our approach is evaluated through classification accuracy on a dataset consisting of problematic prompts not detected by GPT45;4 as well as a selection of contentious but unproblematic prompts. We show considerable increase in classification accuracy of the judge model on this challenging dataset as it undergoes the optimisation process. Furthermore we show that a rudimentary model texttt123;ada125; can achieve 1337; higher accuracy on the hold45;out test set than GPT45;4 after only a few rounds of this process and that this fine45;tuning improves performance in parallel tasks such as toxic comment identification.

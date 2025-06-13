---
layout: publication
title: 'Estimating The Effects Of Sample Training Orders For Large Language Models Without Retraining'
authors: Hao Yang, Haoxuan Li, Mengyue Yang, Xu Chen, Mingming Gong
conference: "Arxiv"
year: 2025
bibkey: yang2025estimating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22042"}
tags: ['Training Techniques', 'Tools']
---
The order of training samples plays a crucial role in large language models (LLMs), significantly impacting both their external performance and internal learning dynamics. Traditional methods for investigating this effect generally require retraining the model with various sample orders, which is computationally infeasible for LLMs. In this work, we improve traditional methods by designing a retraining-free framework. By approximating Adam optimizer updates with first- and second-order Taylor expansions and utilizing random projection methods to store intermediate checkpoints, our framework can efficiently estimate model parameters for arbitrary training sample orders. Next, we apply our framework to two downstream research problems: (1) Training curriculum design for LLMs -- we base our retraining-free framework to propose a novel curriculum learning strategy that augments curriculum proposals with estimated model performances, enabling more informed sample scheduling. (2) LLMs' memorization and generalization effect analysis -- we use our retraining-free framework to estimate how the positions of training samples influence LLMs' capacity for memorization and generalization. We conduct extensive experiments to validate the effectiveness of our retraining-free framework in reproducing the true model performances, and further demonstrate its potential in optimizing LLM training curricula and analyzing the memorization and generalization effects of LLMs.

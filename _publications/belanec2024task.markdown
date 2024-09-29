---
layout: publication
title: Task Prompt Vectors Effective Initialization Through Multi45;task Soft45;prompt Transfer
authors: Belanec Robert, Ostermann Simon, Srba Ivan, Bielikova Maria
conference: "Arxiv"
year: 2024
bibkey: belanec2024task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01119"}
tags: ['Pretraining Methods', 'Prompting', 'Training Techniques']
---
Prompt tuning is a modular and efficient solution for training large language models (LLMs). One of its main advantages is task modularity making it suitable for multi45;task problems. However current soft45;prompt45;based methods often sacrifice multi45;task modularity requiring the training process to be fully or partially repeated for each newly added task. While recent work on task vectors applied arithmetic operations on full model weights to achieve the desired multi45;task performance a similar approach for soft45;prompts is still missing. To this end we introduce Task Prompt Vectors created by element45;wise difference between weights of tuned soft45;prompts and their random initialization. Experimental results on 12 NLU datasets show that task prompt vectors can be used in low45;resource settings to effectively initialize prompt tuning on similar tasks. In addition we show that task prompt vectors are independent of the random initialization of prompt tuning. This allows prompt arithmetics with the pre45;trained vectors from different tasks. In this way by arithmetic addition of task prompt vectors from multiple tasks we are able to outperform a state45;of45;the45;art baseline in some cases.

---
layout: publication
title: 'Improving Cross-task Generalization With Step-by-step Instructions'
authors: Wu Yang, Zhao Yanyan, Li Zhongyang, Qin Bing, Xiong Kai
conference: "Arxiv"
year: 2023
bibkey: wu2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.04429"}
tags: ['GPT', 'Model Architecture', 'Prompting', 'Uncategorized']
---
Instruction tuning has been shown to be able to improve cross-task generalization of language models. However, it is still challenging for language models to complete the target tasks following the instructions, as the instructions are general and lack intermediate steps. To address this problem, we propose to incorporate the step-by-step instructions to help language models to decompose the tasks, which can provide the detailed and specific procedures for completing the target tasks. The step-by-step instructions are obtained automatically by prompting ChatGPT, which are further combined with the original instructions to tune language models. The extensive experiments on SUP-NATINST show that the high-quality step-by-step instructions can improve cross-task generalization across different model sizes. Moreover, the further analysis indicates the importance of the order of steps of the step-by-step instruction for the improvement. To facilitate future research, we release the step-by-step instructions and their human quality evaluation results.

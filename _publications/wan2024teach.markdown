---
layout: publication
title: Teach Better Or Show Smarter On Instructions And Exemplars In Automatic Prompt Optimization
authors: Wan Xingchen, Sun Ruoxi, Nakhost Hootan, Arik Sercan O.
conference: "Arxiv"
year: 2024
bibkey: wan2024teach
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15708"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Prompting']
---
Large language models have demonstrated remarkable capabilities but their performance is heavily reliant on effective prompt engineering. Automatic prompt optimization (APO) methods are designed to automate this and can be broadly categorized into those targeting instructions (instruction optimization IO) vs. those targeting exemplars (exemplar selection ES). Despite their shared objective these have evolved rather independently with IO recently receiving more research attention. This paper seeks to bridge this gap by comprehensively comparing the performance of representative IO and ES techniques both isolation and combination on a diverse set of challenging tasks. Our findings reveal that intelligently reusing model-generated input-output pairs obtained from evaluating prompts on the validation set as exemplars consistently improves performance over IO methods but is currently under-investigated. We also find that despite the recent focus on IO how we select exemplars can outweigh how we optimize instructions with ES strategies as simple as random search outperforming state-of-the-art IO methods with seed instructions without any optimization. Moreover we observe synergy between ES and IO with optimal combinations surpassing individual contributions. We conclude that studying exemplar selection as a standalone method and its optimal combination with instruction optimization remains a crucial aspect of APO and deserves greater consideration in future research even in the era of highly capable instruction-following models.

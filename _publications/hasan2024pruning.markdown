---
layout: publication
title: 'Pruning For Protection: Increasing Jailbreak Resistance In Aligned Llms Without Fine-tuning'
authors: Hasan Adib, Rugina Ileana, Wang Alex
conference: "Arxiv"
year: 2024
bibkey: hasan2024pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10862"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Prompting', 'Pruning', 'Responsible AI', 'Security', 'Training Techniques']
---
Large Language Models (LLMs) are susceptible to jailbreaking prompts which can induce the generation of harmful content. This paper demonstrates that moderate WANDA pruning (Sun et al. 2023) can increase their resistance to such attacks without the need for fine-tuning while maintaining performance on standard benchmarks. Our findings suggest that the benefits of pruning correlate with the initial safety levels of the model indicating a regularizing effect of WANDA pruning. We introduce a dataset of 225 harmful tasks across five categories to systematically evaluate this safety enhancement. We argue that safety improvements can be understood through a regularization perspective. First we show that pruning helps LLMs focus more effectively on task-relevant tokens within jailbreaking prompts. Then we analyze the effects of pruning on the perplexity of malicious prompts before and after their integration into jailbreak templates. Finally we demonstrate statistically significant performance improvements under domain shifts when applying WANDA to linear models.

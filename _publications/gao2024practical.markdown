---
layout: publication
title: Practical Unlearning For Large Language Models
authors: Gao Chongyang, Wang Lixu, Weng Chenkai, Wang Xiao, Zhu Qi
conference: "Arxiv"
year: 2024
bibkey: gao2024practical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10223"}
tags: ['Fine Tuning', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
While LLMs have demonstrated impressive performance across various domains and tasks their security issues have become increasingly severe. Machine unlearning (MU) has emerged as a promising solution to address these issues by removing the influence of undesired data on the target model without compromising its utility in other aspects. MU typically assumes full access to the original training data to preserve utility which is difficult to achieve in LLM unlearning. Existing LLM unlearning methods often assume access to data most affected by undesired data unlearning. However this assumption underestimates the entanglement among various LLM capabilities and ignores data access limitations due to various issues. Moreover these LLM unlearning methods do not sufficiently consider that unlearning requests in real45;world scenarios are continuously emerging. To overcome these challenges and achieve practical LLM unlearning we propose the O3 framework. The O3 framework includes an Out45;Of45;Distribution (OOD) detector to measure the similarity between input and unlearning data and an Orthogonal low45;rank adapter (LoRA) for continuously unlearning requested data. The OOD detector is trained with a novel contrastive entropy loss and utilizes a local45;global layer45;aggregated scoring mechanism. The orthogonal LoRA achieves parameter disentanglement among continual unlearning requests. During inference our O3 framework can smartly decide whether and to what extent to load the unlearning LoRA based on the OOD detectors predictions. Notably O3s effectiveness does not rely on any retained data. We conducted extensive experiments on O3 and state45;of45;the45;art LLM unlearning methods across three tasks and seven datasets. The results indicate that O3 consistently achieves the best trade45;off between unlearning effectiveness and utility preservation especially when facing continuous unlearning requests.

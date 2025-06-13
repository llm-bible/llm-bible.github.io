---
layout: publication
title: 'Budget-adaptive Adapter Tuning In Orthogonal Subspaces For Continual Learning In Llms'
authors: Zhiyi Wan, Wanrou Du, Liang Li, Miao Pan, Xiaoqi Qin
conference: "Arxiv"
year: 2025
bibkey: wan2025budget
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22358"}
tags: ['RAG', 'Training Techniques', 'Efficiency and Optimization']
---
Large language models (LLMs) often suffer from catastrophic forgetting in continual learning (CL) scenarios, where performance on previously learned tasks degrades severely while training on sequentially arriving tasks. Although pioneering CL approaches using orthogonal subspaces can mitigate task interference, they typically employ fixed budget allocation, neglecting the varying complexity across tasks and layers. Besides, recent budget-adaptive tuning methods for LLMs often adopt multi-stage paradigms that decouple optimization and budget allocation. Such decoupling results in potential misalignment, which hinders those approaches' practical application in CL scenarios. To address these limitations, we propose OA-Adapter, a novel parameter-efficient approach for continual learning in LLMs that unifies dynamic budget adaptation with orthogonal subspace learning in a single end-to-end training stage. Specifically, OA-Adapter introduces a dynamic bottleneck dimension adaptation mechanism that simultaneously allocates an efficient parameter budget and optimizes task objectives without misalignment. To effectively preserve previously acquired knowledge while coordinating with the dynamic budget allocation, orthogonal constraints are applied specifically between the parameter subspace of the current task and the dynamically allocated parameter subspaces of historical tasks. Experimental results on continual learning benchmarks demonstrate that OA-Adapter outperforms state-of-the-art methods in both accuracy and parameter efficiency, achieving higher average accuracy while using 58.5% fewer parameters on the standard CL benchmark.

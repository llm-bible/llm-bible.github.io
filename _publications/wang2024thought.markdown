---
layout: publication
title: 'Thought-path Contrastive Learning Via Premise-oriented Data Augmentation For Logical Reading Comprehension'
authors: Chenxu Wang, Ping Jian, Zhen Yang
conference: "Arxiv"
year: 2024
bibkey: wang2024thought
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.14495'}
  - {name: "Code", url: 'https://github.com/lalalamdbf/TPReasoner'}
tags: ['Has Code', 'Tools', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Logical reading comprehension is a challenging task that entails grasping the
underlying semantics of text and applying reasoning to deduce the correct
answer. Prior researches have primarily focused on enhancing logical reasoning
capabilities through Chain-of-Thought (CoT) or data augmentation. However,
previous work constructing chain-of-thought rationales concentrates solely on
analyzing correct options, neglecting the incorrect alternatives. Addtionally,
earlier efforts on data augmentation by altering contexts rely on rule-based
methods, which result in generated contexts that lack diversity and coherence.
To address these issues, we propose a Premise-Oriented Data Augmentation (PODA)
framework. This framework can generate CoT rationales including analyses for
both correct and incorrect options, while constructing diverse and high-quality
counterfactual contexts from incorrect candidate options. We integrate
summarizing premises and identifying premises for each option into rationales.
Subsequently, we employ multi-step prompts with identified premises to
construct counterfactual context. To facilitate the model's capabilities to
better differentiate the reasoning process associated with each option, we
introduce a novel thought-path contrastive learning method that compares
reasoning paths between the original and counterfactual samples. Experimental
results on three representative LLMs demonstrate that our method can improve
the baselines substantially across two challenging logical reasoning benchmarks
(ReClor and LogiQA 2.0). The data and code are released at
https://github.com/lalalamdbf/TPReasoner.

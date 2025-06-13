---
layout: publication
title: 'Fair-pp: A Synthetic Dataset For Aligning LLM With Personalized Preferences Of Social Equity'
authors: Qi Zhou, Jie Zhang, Dongxia Wang, Qiang Liu, Tianlin Li, Jin Song Dong, Wenhai Wang, Qing Guo
conference: "Arxiv"
year: 2025
bibkey: zhou2025fair
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.11861'}
tags: ['RAG', 'Fairness', 'Model Architecture', 'Tools', 'GPT', 'Survey Paper', 'Reinforcement Learning']
---
Human preference plays a crucial role in the refinement of large language models (LLMs). However, collecting human preference feedback is costly and most existing datasets neglect the correlation between personalization and preferences. To address this issue, we introduce Fair-PP, a synthetic dataset of personalized preferences targeting social equity, derived from real-world social survey data, which includes 28 social groups, 98 equity topics, and 5 personal preference dimensions. Leveraging GPT-4o-mini, we engage in role-playing based on seven representative persona portrayals guided by existing social survey data, yielding a total of 238,623 preference records. Through Fair-PP, we also contribute (i) An automated framework for generating preference data, along with a more fine-grained dataset of personalized preferences; (ii) analysis of the positioning of the existing mainstream LLMs across five major global regions within the personalized preference space; and (iii) a sample reweighting method for personalized preference alignment, enabling alignment with a target persona while maximizing the divergence from other personas. Empirical experiments show our method outperforms the baselines.

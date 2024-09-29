---
layout: publication
title: Democratizing Large Language Models Via Personalized Parameter45;efficient Fine45;tuning
authors: Tan Zhaoxuan, Zeng Qingkai, Tian Yijun, Liu Zheyuan, Yin Bing, Jiang Meng
conference: "Arxiv"
year: 2024
bibkey: tan2024democratizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04401"}
tags: ['Prompting', 'Security']
---
Personalization in large language models (LLMs) is increasingly important aiming to align LLMs interactions content and recommendations with individual user preferences. Recent advances in LLM personalization have spotlighted effective prompt design by enriching user queries with non45;parametric knowledge through behavior history retrieval and textual profiles. However these approaches were limited due to a lack of model ownership resulting in constrained customization and privacy issues. Moreover they often failed to accurately capture user behavior patterns especially in cases where user data were complex and dynamic. To address these shortcomings we introduce One PEFT Per User (OPPU) which employs personalized parameter45;efficient fine45;tuning (PEFT) modules to store user45;specific behavior patterns and preferences. By plugging in users personal PEFT parameters they can own and use their LLMs personally. OPPU integrates parametric user knowledge in the personal PEFT parameters with the non45;parametric knowledge acquired through retrieval and profile. This integration adapts individual LLMs to user behavior shifts. Experimental results demonstrate that OPPU significantly outperforms existing prompt45;based methods across seven diverse tasks in the LaMP benchmark. Further in45;depth studies reveal OPPUs enhanced capabilities in handling user behavior shifts modeling users at different active levels maintaining robustness across various user history formats and displaying versatility with different PEFT methods.

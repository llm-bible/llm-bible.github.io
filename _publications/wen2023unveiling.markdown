---
layout: publication
title: Unveiling The Implicit Toxicity In Large Language Models
authors: Wen Jiaxin, Ke Pei, Sun Hao, Zhang Zhexin, Li Chengfei, Bai Jinfeng, Huang Minlie
conference: "Arxiv"
year: 2023
bibkey: wen2023unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.17391"}
  - {name: "Code", url: "https://github.com/thu&#45;coai/Implicit&#45;Toxicity"}
tags: ['Agentic', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Security']
---
The open45;endedness of large language models (LLMs) combined with their impressive capabilities may lead to new safety issues when being exploited for malicious use. While recent studies primarily focus on probing toxic outputs that can be easily detected with existing toxicity classifiers we show that LLMs can generate diverse implicit toxic outputs that are exceptionally difficult to detect via simply zero45;shot prompting. Moreover we propose a reinforcement learning (RL) based attacking method to further induce the implicit toxicity in LLMs. Specifically we optimize the language model with a reward that prefers implicit toxic outputs to explicit toxic and non45;toxic ones. Experiments on five widely45;adopted toxicity classifiers demonstrate that the attack success rate can be significantly improved through RL fine45;tuning. For instance the RL45;finetuned LLaMA45;13B model achieves an attack success rate of 90.0437; on BAD and 62.8537; on Davinci003. Our findings suggest that LLMs pose a significant threat in generating undetectable implicit toxic outputs. We further show that fine45;tuning toxicity classifiers on the annotated examples from our attacking method can effectively enhance their ability to detect LLM45;generated implicit toxic language. The code is publicly available at https://github.com/thu&#45;coai/Implicit&#45;Toxicity.

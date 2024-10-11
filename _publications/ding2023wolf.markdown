---
layout: publication
title: 'A Wolf In Sheep''s Clothing: Generalized Nested Jailbreak Prompts Can Fool Large Language Models Easily'
authors: Ding Peng, Kuang Jun, Ma Dan, Cao Xuezhi, Xian Yunsen, Chen Jiajun, Huang Shujian
conference: "Arxiv"
year: 2023
bibkey: ding2023wolf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08268"}
  - {name: "Code", url: "https://github.com/NJUNLP/ReNeLLM"}
tags: ['Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Security', 'Tools', 'Uncategorized']
---
Large Language Models (LLMs), such as ChatGPT and GPT-4, are designed to provide useful and safe responses. However, adversarial prompts known as 'jailbreaks' can circumvent safeguards, leading LLMs to generate potentially harmful content. Exploring jailbreak prompts can help to better reveal the weaknesses of LLMs and further steer us to secure them. Unfortunately, existing jailbreak methods either suffer from intricate manual design or require optimization on other white-box models, which compromises either generalization or efficiency. In this paper, we generalize jailbreak prompt attacks into two aspects: (1) Prompt Rewriting and (2) Scenario Nesting. Based on this, we propose ReNeLLM, an automatic framework that leverages LLMs themselves to generate effective jailbreak prompts. Extensive experiments demonstrate that ReNeLLM significantly improves the attack success rate while greatly reducing the time cost compared to existing baselines. Our study also reveals the inadequacy of current defense methods in safeguarding LLMs. Finally, we analyze the failure of LLMs defense from the perspective of prompt execution priority, and propose corresponding defense strategies. We hope that our research can catalyze both the academic community and LLMs developers towards the provision of safer and more regulated LLMs. The code is available at https://github.com/NJUNLP/ReNeLLM.

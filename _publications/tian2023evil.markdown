---
layout: publication
title: Evil Geniuses Delving Into The Safety Of Llm-based Agents
authors: Tian Yu, Yang Xiao, Zhang Jingyuan, Dong Yinpeng, Su Hang
conference: "Arxiv"
year: 2023
bibkey: tian2023evil
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.11855"}
  - {name: "Code", url: "https://github.com/T1aNS1R/Evil-Geniuses"}
tags: ['Agent', 'Agentic', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Responsible AI', 'Security', 'Tools']
---
Rapid advancements in large language models (LLMs) have revitalized in LLM-based agents exhibiting impressive human-like behaviors and cooperative capabilities in various scenarios. However these agents also bring some exclusive risks stemming from the complexity of interaction environments and the usability of tools. This paper delves into the safety of LLM-based agents from three perspectives agent quantity role definition and attack level. Specifically we initially propose to employ a template-based attack strategy on LLM-based agents to find the influence of agent quantity. In addition to address interaction environment and role specificity issues we introduce Evil Geniuses (EG) an effective attack method that autonomously generates prompts related to the original role to examine the impact across various role definitions and attack levels. EG leverages Red-Blue exercises significantly improving the generated prompt aggressiveness and similarity to original roles. Our evaluations on CAMEL Metagpt and ChatDev based on GPT-3.5 and GPT-4 demonstrate high success rates. Extensive evaluation and discussion reveal that these agents are less robust prone to more harmful behaviors and capable of generating stealthier content than LLMs highlighting significant safety challenges and guiding future research. Our code is available at https://github.com/T1aNS1R/Evil-Geniuses.

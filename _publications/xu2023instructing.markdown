---
layout: publication
title: 'Expertprompting: Instructing Large Language Models To Be Distinguished Experts'
authors: Xu Benfeng, Yang An, Lin Junyang, Wang Quan, Zhou Chang, Zhang Yongdong, Mao Zhendong
conference: "Arxiv"
year: 2023
bibkey: xu2023instructing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14688"}
  - {name: "Code", url: "https://github.com/OFA-Sys/ExpertLLaMA"}
tags: ['Agentic', 'GPT', 'Has Code', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
The answering quality of an aligned large language model (LLM) can be drastically improved if treated with proper crafting of prompts. In this paper we propose ExpertPrompting to elicit the potential of LLMs to answer as distinguished experts. We first utilize In-Context Learning to automatically synthesize detailed and customized descriptions of the expert identity for each specific instruction and then ask LLMs to provide answer conditioned on such agent background. Based on this augmented prompting strategy we produce a new set of instruction-following data using GPT-3.5 and train a competitive open-source chat assistant called ExpertLLaMA. We employ GPT4-based evaluation to show that 1) the expert data is of significantly higher quality than vanilla answers and 2) ExpertLLaMA outperforms existing open-source opponents and achieves 9637; of the original ChatGPTs capability. All data and the ExpertLLaMA model will be made publicly available at (url)https://github.com/OFA-Sys/ExpertLLaMA\}."

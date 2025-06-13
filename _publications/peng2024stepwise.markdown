---
layout: publication
title: 'Stepwise Reasoning Error Disruption Attack Of Llms'
authors: Jingyu Peng, Maolin Wang, Xiangyu Zhao, Kai Zhang, Wanyu Wang, Pengyue Jia, Qidong Liu, Ruocheng Guo, Qi Liu
conference: "Arxiv"
year: 2024
bibkey: peng2024stepwise
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.11934'}
  - {name: "Code", url: 'https://github.com/Applied-Machine-Learning-Lab/SEED-Attack'}
tags: ['Attention Mechanism', 'Has Code', 'Few-Shot', 'Security', 'Applications', 'Model Architecture', 'Responsible AI']
---
Large language models (LLMs) have made remarkable strides in complex reasoning tasks, but their safety and robustness in reasoning processes remain underexplored. Existing attacks on LLM reasoning are constrained by specific settings or lack of imperceptibility, limiting their feasibility and generalizability. To address these challenges, we propose the Stepwise rEasoning Error Disruption (SEED) attack, which subtly injects errors into prior reasoning steps to mislead the model into producing incorrect subsequent reasoning and final answers. Unlike previous methods, SEED is compatible with zero-shot and few-shot settings, maintains the natural reasoning flow, and ensures covert execution without modifying the instruction. Extensive experiments on four datasets across four different models demonstrate SEED's effectiveness, revealing the vulnerabilities of LLMs to disruptions in reasoning processes. These findings underscore the need for greater attention to the robustness of LLM reasoning to ensure safety in practical applications. Our code is available at: https://github.com/Applied-Machine-Learning-Lab/SEED-Attack.

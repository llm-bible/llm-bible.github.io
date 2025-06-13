---
layout: publication
title: 'Proactive Agent: Shifting LLM Agents From Reactive Responses To Active Assistance'
authors: Yaxi Lu, Shenzhi Yang, Cheng Qian, Guirong Chen, Qinyu Luo, Yesai Wu, Huadong Wang, Xin Cong, Zhong Zhang, Yankai Lin, Weiwen Liu, Yasheng Wang, Zhiyuan Liu, Fangming Liu, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: lu2024proactive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12361"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
Agents powered by large language models have shown remarkable abilities in
solving complex tasks. However, most agent systems remain reactive, limiting
their effectiveness in scenarios requiring foresight and autonomous
decision-making. In this paper, we tackle the challenge of developing proactive
agents capable of anticipating and initiating tasks without explicit human
instructions. We propose a novel data-driven approach for this problem.
Firstly, we collect real-world human activities to generate proactive task
predictions. These predictions are then labeled by human annotators as either
accepted or rejected. The labeled data is used to train a reward model that
simulates human judgment and serves as an automatic evaluator of the
proactiveness of LLM agents. Building on this, we develop a comprehensive data
generation pipeline to create a diverse dataset, ProactiveBench, containing
6,790 events. Finally, we demonstrate that fine-tuning models with the proposed
ProactiveBench can significantly elicit the proactiveness of LLM agents.
Experimental results show that our fine-tuned model achieves an F1-Score of
66.47% in proactively offering assistance, outperforming all open-source and
close-source models. These results highlight the potential of our method in
creating more proactive and effective agent systems, paving the way for future
advancements in human-agent collaboration.

---
layout: publication
title: 'Evaluating And Enhancing Large Language Models For Conversational Reasoning On Knowledge Graphs'
authors: Huang Yuxuan, Shi Lida, Liu Anqi, Xu Hao
conference: "Arxiv"
year: 2023
bibkey: huang2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11282"}
  - {name: "Code", url: "https://github.com/Aipura/LLM-ARK)"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
The development of large language models (LLMs) has been catalyzed by
advancements in pre-training techniques. These models have demonstrated robust
reasoning capabilities through manually designed prompts. In this work, we
evaluate the conversational reasoning capabilities of the current
state-of-the-art LLM (GPT-4) on knowledge graphs (KGs). However, the
performance of LLMs is constrained due to a lack of KG environment awareness
and the difficulties in developing effective optimization mechanisms for
intermediary reasoning stages. We further introduce LLM-ARK, a LLM grounded KG
reasoning agent designed to deliver precise and adaptable predictions on KG
paths. LLM-ARK leverages Full Textual Environment (FTE) prompt to assimilate
state information within each reasoning step. We reframe the challenge of
multi-hop reasoning on the KG as a sequential decision-making task. Utilizing
the Proximal Policy Optimization (PPO) online policy gradient reinforcement
learning algorithm, our model is optimized to learn from rich reward signals.
Additionally, we conduct an evaluation of our model and GPT-4 on the OpenDialKG
dataset. The experimental results reveal that LLaMA-2-7B-ARK outperforms the
current state-of-the-art model by 5.28 percentage points, with a performance
rate of 36.39% on the target@1 evaluation metric. Meanwhile, GPT-4 scored
14.91%, further demonstrating the effectiveness of our method. Our code is
available on GitHub (https://github.com/Aipura/LLM-ARK) for further access.

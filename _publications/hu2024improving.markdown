---
layout: publication
title: 'Improving The Language Understanding Capabilities Of Large Language Models Using Reinforcement Learning'
authors: Bokai Hu, Sai Ashish Somayajula, Xin Pan, Pengtao Xie
conference: "Arxiv"
year: 2024
bibkey: hu2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11020"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'BERT', 'Fine-Tuning', 'Prompting', 'Applications', 'In-Context Learning']
---
Instruction-fine-tuned large language models (LLMs) under 14B parameters continue to underperform on natural language understanding (NLU) tasks, often trailing smaller models like BERT-base on benchmarks such as GLUE and SuperGLUE. Motivated by the success of reinforcement learning in reasoning tasks (e.g., DeepSeek), we explore Proximal Policy Optimization (PPO) as a framework to improve the NLU capabilities of LLMs. We frame NLU as a reinforcement learning environment, treating token generation as a sequence of actions and optimizing for reward signals based on alignment with ground-truth labels. PPO consistently outperforms supervised fine-tuning, yielding an average improvement of 6.3 points on GLUE, and surpasses zero-shot and few-shot prompting by 38.7 and 26.1 points, respectively. Notably, PPO-tuned models outperform GPT-4o by over 4% on average across sentiment and natural language inference tasks, including gains of 7.3% on the Mental Health dataset and 10.9% on SIGA-nli. This work highlights a promising direction for adapting LLMs to new tasks by reframing them as reinforcement learning problems, enabling learning through simple end-task rewards rather than extensive data curation.

---
layout: publication
title: 'Self-prompt Tuning: Enable Autonomous Role-playing In Llms'
authors: Aobo Kong, Shiwan Zhao, Hao Chen, Qicheng Li, Yong Qin, Ruiqi Sun, Xin Zhou, Jiaming Zhou, Haoqin Sun
conference: "Arxiv"
year: 2024
bibkey: kong2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.08995"}
  - {name: "Code", url: "https://anonymous.4open.science/r/Self-Prompt-Tuning-739E/}{url"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting']
---
Recent advancements in LLMs have showcased their remarkable role-playing
capabilities, able to accurately simulate the dialogue styles and cognitive
processes of various roles based on different instructions and contexts.
Studies indicate that assigning LLMs the roles of experts, a strategy known as
role-play prompting, can enhance their performance in the corresponding
domains. However, the prompt needs to be manually designed for the given
problem, requiring certain expertise and iterative modifications. To this end,
we propose self-prompt tuning, making LLMs themselves generate role-play
prompts through fine-tuning. Leveraging the LIMA dataset as our foundational
corpus, we employ GPT-4 to annotate role-play prompts for each data points,
resulting in the creation of the LIMA-Role dataset. We then fine-tune LLMs like
Llama-2-7B and Mistral-7B on LIMA-Role. Consequently, the self-prompt tuned
LLMs can automatically generate expert role prompts for any given question. We
extensively evaluate self-prompt tuned LLMs on widely used NLP benchmarks and
open-ended question test. Our empirical results illustrate that self-prompt
tuned LLMs outperform standard instruction tuned baselines across most
datasets. This highlights the great potential of utilizing fine-tuning to
enable LLMs to self-prompt, thereby automating complex prompting strategies. We
release the dataset, models, and code at this
\href\{https://anonymous.4open.science/r/Self-Prompt-Tuning-739E/\}\{url\}.

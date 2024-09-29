---
layout: publication
title: Chinese Open Instruction Generalist A Preliminary Release
authors: Zhang Ge, Shi Yemin, Liu Ruibo, Yuan Ruibin, Li Yizhi, Dong Siwei, Shu Yu, Li Zhaoqun, Wang Zekun, Lin Chenghua, Huang Wenhao, Fu Jie
conference: "Arxiv"
year: 2023
bibkey: zhang2023chinese
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.07987"}
  - {name: "Code", url: "https://github.com/BAAI-Zlab/COIG,"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Instruction tuning is widely recognized as a key technique for building generalist language models which has attracted the attention of researchers and the public with the release of InstructGPT~citepouyang2022training and ChatGPTfootnoteurl https://chat.openai.com/. Despite impressive progress in English-oriented large-scale language models (LLMs) it is still under-explored whether English-based foundation LLMs can perform similarly on multilingual tasks compared to English tasks with well-designed instruction tuning and how we can construct the corpora needed for the tuning. To remedy this gap we propose the project as an attempt to create a Chinese instruction dataset by various methods adapted to the intrinsic characteristics of 4 sub-tasks. We collect around 200k Chinese instruction tuning samples which have been manually checked to guarantee high quality. We also summarize the existing English and Chinese instruction corpora and briefly describe some potential applications of the newly constructed Chinese instruction corpora. The resulting textbfChinese textbfOpen textbfInstruction textbfGeneralist (textbfCOIG) corpora are available in Huggingfacefootnoteurl https://huggingface.co/datasets/BAAI/COIG and Githubfootnoteurl https://github.com/BAAI-Zlab/COIG, and will be continuously updated.

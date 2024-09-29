---
layout: publication
title: AlpaCareInstruction-tuned Large Language Models for Medical Application
authors: Zhang Xinlu, Tian Chenxin, Yang Xianjun, Chen Lichang, Li Zekun, Petzold Linda Ruth
conference: "Arxiv"
year: 2023
bibkey: zhang2023alpacareinstruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14558"}
  - {name: "Code", url: "https://github.com/XZhang97666/AlpaCare"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
Instruction-finetuning (IFT) has become crucial in aligning Large Language Models (LLMs) with diverse human needs and has shown great potential in medical applications. However previous studies mainly fine-tune LLMs on biomedical datasets with limited diversity which often rely on benchmarks or narrow task scopes and hence significantly limit the effectiveness on their medical instruction-following ability and generalizability. To bridge this gap we propose creating a diverse machine-generated medical IFT dataset MedInstruct-52k using GPT-4 and ChatGPT with a high-quality expert-curated seed set. We then fine-tune LLaMA-series models on the dataset to develop AlpaCare. Despite using a smaller domain-specific dataset than previous medical LLMs AlpaCare not only demonstrates superior performance on medical applications with up to 38.1 absolute gain over best baselines in medical free-form instruction evaluations but also achieves 6.7 absolute gains averaged over multiple general domain benchmarks. Human evaluation further shows that AlpaCare consistently outperforms best baselines in terms of both correctness and helpfulness. We offer public access to our data model and codebase in https://github.com/XZhang97666/AlpaCare.

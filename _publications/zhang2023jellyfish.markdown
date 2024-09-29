---
layout: publication
title: Jellyfish A Large Language Model for Data Preprocessing
authors: Zhang Haochen, Dong Yuyang, Xiao Chuan, Oyamada Masafumi
conference: "Arxiv"
year: 2023
bibkey: zhang2023jellyfish
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01678"}
tags: ['Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Security', 'Tools']
---
This paper explores the utilization of LLMs for data preprocessing (DP) a crucial step in the data mining pipeline that transforms raw data into a clean format conducive to easy processing. Whereas the use of LLMs has sparked interest in devising universal solutions to DP recent initiatives in this domain typically rely on GPT APIs raising inevitable data breach concerns. Unlike these approaches we consider instruction-tuning local LLMs (7 -- 13B models) as universal DP task solvers that operate on a local single and low-priced GPU ensuring data security and enabling further customization. We select a collection of datasets across four representative DP tasks and construct instruction tuning data using data configuration knowledge injection and reasoning data distillation techniques tailored to DP. By tuning Mistral-7B Llama 3-8B and OpenOrca-Platypus2-13B our models namely Jellyfish-7B/8B/13B deliver competitiveness compared to GPT-3.5/4 models and strong generalizability to unseen tasks while barely compromising the base models abilities in NLP tasks. Meanwhile Jellyfish offers enhanced reasoning capabilities compared to GPT-3.5. Our models are available at https://huggingface.co/NECOUDBFM/Jellyfish . Our instruction dataset is available at https://huggingface.co/datasets/NECOUDBFM/Jellyfish-Instruct .

---
layout: publication
title: "Towards Evaluating And Building Versatile Large Language Models For Medicine"
authors: Wu Chaoyi, Qiu Pengcheng, Liu Jinxin, Gu Hongfei, Li Na, Zhang Ya, Wang Yanfeng, Xie Weidi
conference: "Arxiv"
year: 2024
bibkey: wu2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12547"}
  - {name: "Code", url: "https://henrychur.github.io/MedS-Bench/"}
  - {name: "Code", url: "https://github.com/MAGIC-AI4Med/MedS-Ins"}
tags: ['Applications', 'Few Shot', 'GPT', 'Has Code', 'In Context Learning', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
In this study we present MedS-Bench a comprehensive benchmark designed to evaluate the performance of large language models (LLMs) in clinical contexts. Unlike existing benchmarks that focus on multiple-choice question answering MedS-Bench spans 11 high-level clinical tasks including clinical report summarization treatment recommendations diagnosis named entity recognition and medical concept explanation among others. We evaluated six leading LLMs e.g. MEDITRON Mistral InternLM 2 Llama 3 GPT-4 and Claude-3.5 using few-shot prompting and found that even the most sophisticated models struggle with these complex tasks. To address these limitations we developed MedS-Ins a large-scale instruction tuning dataset for medicine. MedS-Ins comprises 58 medically oriented language corpora totaling 13.5 million samples across 122 tasks. To demonstrate the datasets utility we conducted a proof-of-concept experiment by performing instruction tuning on a lightweight open-source medical language model. The resulting model MMedIns-Llama 3 significantly outperformed existing models across nearly all clinical tasks. To promote further advancements in the application of LLMs to clinical challenges we have made the MedS-Ins dataset fully accessible and invite the research community to contribute to its expansion.Additionally we have launched a dynamic leaderboard for MedS-Bench which we plan to regularly update the test set to track progress and enhance the adaptation of general LLMs to the medical domain. Leaderboard https://henrychur.github.io/MedS-Bench/. Github https://github.com/MAGIC-AI4Med/MedS-Ins."

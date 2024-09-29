---
layout: publication
title: Towards Evaluating And Building Versatile Large Language Models For Medicine
authors: Wu Chaoyi, Qiu Pengcheng, Liu Jinxin, Gu Hongfei, Li Na, Zhang Ya, Wang Yanfeng, Xie Weidi
conference: "Arxiv"
year: 2024
bibkey: wu2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.12547"}
  - {name: "Code", url: "https://henrychur.github.io/MedS&#45;Bench/"}
  - {name: "Code", url: "https://github.com/MAGIC&#45;AI4Med/MedS&#45;Ins"}
tags: ['Applications', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
In this study we present MedS45;Bench a comprehensive benchmark designed to evaluate the performance of large language models (LLMs) in clinical contexts. Unlike existing benchmarks that focus on multiple45;choice question answering MedS45;Bench spans 11 high45;level clinical tasks including clinical report summarization treatment recommendations diagnosis named entity recognition and medical concept explanation among others. We evaluated six leading LLMs e.g. MEDITRON Mistral InternLM 2 Llama 3 GPT45;4 and Claude45;3.5 using few45;shot prompting and found that even the most sophisticated models struggle with these complex tasks. To address these limitations we developed MedS45;Ins a large45;scale instruction tuning dataset for medicine. MedS45;Ins comprises 58 medically oriented language corpora totaling 13.5 million samples across 122 tasks. To demonstrate the datasets utility we conducted a proof45;of45;concept experiment by performing instruction tuning on a lightweight open45;source medical language model. The resulting model MMedIns45;Llama 3 significantly outperformed existing models across nearly all clinical tasks. To promote further advancements in the application of LLMs to clinical challenges we have made the MedS45;Ins dataset fully accessible and invite the research community to contribute to its expansion.Additionally we have launched a dynamic leaderboard for MedS45;Bench which we plan to regularly update the test set to track progress and enhance the adaptation of general LLMs to the medical domain. Leaderboard https://henrychur.github.io/MedS&#45;Bench/. Github https://github.com/MAGIC&#45;AI4Med/MedS&#45;Ins.

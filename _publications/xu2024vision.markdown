---
layout: publication
title: Vision45;flan Scaling Human45;labeled Tasks In Visual Instruction Tuning
authors: Xu Zhiyang, Feng Chao, Shao Rulin, Ashby Trevor, Shen Ying, Jin Di, Cheng Yu, Wang Qifan, Huang Lifu
conference: "Arxiv"
year: 2024
bibkey: xu2024vision
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11690"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Despite vision45;language models (VLMs) remarkable capabilities as versatile visual assistants two substantial challenges persist within the existing VLM frameworks (1) lacking task diversity in pretraining and visual instruction tuning and (2) annotation error and bias in GPT45;4 synthesized instruction tuning data. Both challenges lead to issues such as poor generalizability hallucination and catastrophic forgetting. To address these challenges we construct Vision45;Flan the most diverse publicly available visual instruction tuning dataset to date comprising 187 diverse tasks and 1664261 instances sourced from academic datasets and each task is accompanied by an expert45;written instruction. In addition we propose a two45;stage instruction tuning framework in which VLMs are firstly finetuned on Vision45;Flan and further tuned on GPT45;4 synthesized data. We find this two45;stage tuning framework significantly outperforms the traditional single45;stage visual instruction tuning framework and achieves the state45;of45;the45;art performance across a wide range of multi45;modal evaluation benchmarks. Finally we conduct in45;depth analyses to understand visual instruction tuning and our findings reveal that (1) GPT45;4 synthesized data does not substantially enhance VLMs capabilities but rather modulates the models responses to human45;preferred formats; (2) A minimal quantity (e.g. 1000) of GPT45;4 synthesized data can effectively align VLM responses with human45;preference; (3) Visual instruction tuning mainly helps large45;language models (LLMs) to understand visual features.

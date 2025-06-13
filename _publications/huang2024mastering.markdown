---
layout: publication
title: 'MUSTARD: Mastering Uniform Synthesis Of Theorem And Proof Data'
authors: Yinya Huang, Xiaohan Lin, Zhengying Liu, Qingxing Cao, Huajian Xin, Haiming Wang, Zhenguo Li, Linqi Song, Xiaodan Liang
conference: "ICLR 2024 spotlight"
year: 2024
bibkey: huang2024mastering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.08957"}
  - {name: "Code", url: "https://github.com/Eleanor-H/MUSTARD"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
Recent large language models (LLMs) have witnessed significant advancement in
various tasks, including mathematical reasoning and theorem proving. As these
two tasks require strict and formal multi-step inference, they are appealing
domains for exploring the reasoning ability of LLMs but still face important
challenges. Previous studies such as Chain-of-Thought (CoT) have revealed the
effectiveness of intermediate steps guidance. However, such step-wise
annotation requires heavy labor, leading to insufficient training steps for
current benchmarks. To fill this gap, this work introduces MUSTARD, a data
generation framework that masters uniform synthesis of theorem and proof data
of high quality and diversity. MUSTARD synthesizes data in three stages: (1) It
samples a few mathematical concept seeds as the problem category. (2) Then, it
prompts a generative language model with the sampled concepts to obtain both
the problems and their step-wise formal solutions. (3) Lastly, the framework
utilizes a proof assistant (e.g., Lean Prover) to filter the valid proofs. With
the proposed MUSTARD, we present a theorem-and-proof benchmark MUSTARDSAUCE
with 5,866 valid data points. Each data point contains an informal statement,
an informal proof, and a translated formal proof that passes the prover
validation. We perform extensive analysis and demonstrate that MUSTARD
generates validated high-quality step-by-step data. We further apply the
MUSTARDSAUCE for fine-tuning smaller language models. The fine-tuned Llama 2-7B
achieves a 15.41% average relative performance gain in automated theorem
proving, and 8.18% in math word problems. Codes and data are available at
https://github.com/Eleanor-H/MUSTARD.

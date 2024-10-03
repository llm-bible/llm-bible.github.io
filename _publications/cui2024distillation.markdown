---
layout: publication
title: 'Distillation Matters: Empowering Sequential Recommenders To Match The Performance Of Large Language Model'
authors: Cui Yu, Liu Feng, Wang Pengbo, Wang Bohao, Tang Heng, Wan Yi, Wang Jun, Chen Jiawei
conference: "Arxiv"
year: 2024
bibkey: cui2024distillation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00338"}
tags: ['Distillation', 'Efficiency And Optimization', 'RAG']
---
Owing to their powerful semantic reasoning capabilities, Large Language Models (LLMs) have been effectively utilized as recommenders, achieving impressive performance. However, the high inference latency of LLMs significantly restricts their practical deployment. To address this issue, this work investigates knowledge distillation from cumbersome LLM-based recommendation models to lightweight conventional sequential models. It encounters three challenges: 1) the teacher's knowledge may not always be reliable; 2) the capacity gap between the teacher and student makes it difficult for the student to assimilate the teacher's knowledge; 3) divergence in semantic space poses a challenge to distill the knowledge from embeddings. To tackle these challenges, this work proposes a novel distillation strategy, DLLM2Rec, specifically tailored for knowledge distillation from LLM-based recommendation models to conventional sequential models. DLLM2Rec comprises: 1) Importance-aware ranking distillation, which filters reliable and student-friendly knowledge by weighting instances according to teacher confidence and student-teacher consistency; 2) Collaborative embedding distillation integrates knowledge from teacher embeddings with collaborative signals mined from the data. Extensive experiments demonstrate the effectiveness of the proposed DLLM2Rec, boosting three typical sequential models with an average improvement of 47.97&#37;, even enabling them to surpass LLM-based recommenders in some cases.

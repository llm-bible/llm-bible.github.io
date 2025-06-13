---
layout: publication
title: 'Frabench And Geneval: Scaling Fine-grained Aspect Evaluation Across Tasks, Modalities'
authors: Shibo Hong, Jiahao Ying, Haiyuan Liang, Mengdi Zhang, Jun Kuang, Jiazheng Zhang, Yixin Cao
conference: "Arxiv"
year: 2025
bibkey: hong2025frabench
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12795"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Evaluating the open-ended outputs of large language models (LLMs) has become a bottleneck as model capabilities, task diversity, and modality coverage rapidly expand. Existing "LLM-as-a-Judge" evaluators are typically narrow in a few tasks, aspects, or modalities, and easily suffer from low consistency. In this paper, we argue that explicit, fine-grained aspect specification is the key to both generalizability and objectivity in automated evaluation. To this end, we propose a hierarchical aspect taxonomy encompassing 112 distinct aspects that unifies evaluation across four representative settings -- Natural Language Generation, Image Understanding, Image Generation, and Interleaved Text-and-Image Generation. Building upon this taxonomy, we create FRABench, a benchmark comprising 60.4k pairwise samples with 325k evaluation labels obtained from a combination of human and LLM annotations. FRABench provides the first large-scale, multi-modal resource for training and meta-evaluating fine-grained LMM judges. Leveraging FRABench, we develop GenEval, a fine-grained evaluator generalizable across tasks and modalities. Experiments show that GenEval (i) attains high agreement with GPT-4o and expert annotators, (ii) transfers robustly to unseen tasks and modalities, and (iii) reveals systematic weaknesses of current LMMs on evaluation.

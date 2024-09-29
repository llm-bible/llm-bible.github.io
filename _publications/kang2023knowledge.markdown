---
layout: publication
title: Knowledge45;augmented Reasoning Distillation For Small Language Models In Knowledge45;intensive Tasks
authors: Kang Minki, Lee Seanie, Baek Jinheon, Kawaguchi Kenji, Hwang Sung Ju
conference: "Arxiv"
year: 2023
bibkey: kang2023knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18395"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown promising performance in knowledge45;intensive reasoning tasks that require a compound understanding of knowledge. However deployment of the LLMs in real45;world applications can be challenging due to their high computational requirements and concerns on data privacy. Previous studies have focused on building task45;specific small Language Models (LMs) by fine45;tuning them with labeled data or distilling LLMs. However these approaches are ill45;suited for knowledge45;intensive reasoning tasks due to the limited capacity of small LMs in memorizing the knowledge required. Motivated by our theoretical analysis on memorization we propose Knowledge45;Augmented Reasoning Distillation (KARD) a novel method that fine45;tunes small LMs to generate rationales obtained from LLMs with augmented knowledge retrieved from an external knowledge base. Moreover we further propose a neural reranker to obtain documents relevant to rationale generation. We empirically show that KARD significantly improves the performance of small T5 and GPT models on the challenging knowledge45;intensive reasoning datasets namely MedQA45;USMLE StrategyQA and OpenbookQA. Notably our method makes the 250M T5 models achieve superior performance against the fine45;tuned 3B models having 12 times larger parameters on both MedQA45;USMLE and StrategyQA benchmarks.

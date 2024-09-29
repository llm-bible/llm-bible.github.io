---
layout: publication
title: Mathscale Scaling Instruction Tuning For Mathematical Reasoning
authors: Tang Zhengyang, Zhang Xingxing, Wang Benyou, Wei Furu
conference: "Arxiv"
year: 2024
bibkey: tang2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02884"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
Large language models (LLMs) have demonstrated remarkable capabilities in problem45;solving. However their proficiency in solving mathematical problems remains inadequate. We propose MathScale a simple and scalable method to create high45;quality mathematical reasoning data using frontier LLMs (e.g. 123;tt GPT45;3.5125;). Inspired by the cognitive mechanism in human mathematical learning it first extracts topics and knowledge points from seed math questions and then build a concept graph which is subsequently used to generate new math questions. MathScale exhibits effective scalability along the size axis of the math dataset that we generate. As a result we create a mathematical reasoning dataset (MathScaleQA) containing two million math question45;answer pairs. To evaluate mathematical reasoning abilities of LLMs comprehensively we construct 123;sc MwpBench125; a benchmark of Math Word Problems which is a collection of ten datasets (including GSM8K and MATH) covering K45;12 college and competition level math problems. We apply MathScaleQA to fine45;tune open45;source LLMs (e.g. LLaMA45;2 and Mistral) resulting in significantly improved capabilities in mathematical reasoning. Evaluated on 123;sc MwpBench125; MathScale45;7B achieves state45;of45;the45;art performance across all datasets surpassing its best peers of equivalent size by 42.937; in micro average accuracy and 43.737; in macro average accuracy respectively.

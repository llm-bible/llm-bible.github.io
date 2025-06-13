---
layout: publication
title: 'Optimizing Alignment With Less: Leveraging Data Augmentation For Personalized Evaluation'
authors: Javad Seraj, Mohammad Mahdi Mohajeri, Mohammad Javad Dousti, Majid Nili Ahmadabadi
conference: "Arxiv"
year: 2024
bibkey: seraj2024optimizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07429'}
tags: ['Reinforcement Learning', 'RAG']
---
Automatic evaluation by large language models (LLMs) is a prominent topic
today; however, judgment and evaluation tasks are often subjective and
influenced by various factors, making adaptation challenging. While many
studies demonstrate the capabilities of state-of-the-art proprietary LLMs in
comparison to human evaluators, they often struggle to adapt to reference
evaluators over time, a requirement for achieving personalized judgment.
Additionally, numerous works have attempted to apply open LLMs as judges or
evaluators, but these efforts frequently overlook the limitations of working
with scarce data. Personalized judgment is inherently associated with limited
data scenarios, which are common in many real-world problems. Our work aims to
present a data augmentation technique to select a more effective sample from
limited data in order to align an open LLM with human preference. Our work
achieves approximately 7% improvements in Pearson correlation with a reference
judge over the baseline,and 30% improvement over the base model
(Llama3.1-8B-Instruct) in the mathematical reasoning evaluation task.
demonstrating that augmenting selecting more effective preference data enables
our approach to surpass baseline methods.

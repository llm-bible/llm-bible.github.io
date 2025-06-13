---
layout: publication
title: 'Rankprompt: Step-by-step Comparisons Make Language Models Better Reasoners'
authors: Chi Hu, Yuan Ge, Xiangnan Ma, Hang Cao, Qiang Li, Yonghua Yang, Tong Xiao, Jingbo Zhu
conference: "Arxiv"
year: 2024
bibkey: hu2024step
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12373"}
tags: ['Security', 'Model Architecture', 'RAG', 'GPT', 'Prompting']
---
Large Language Models (LLMs) have achieved impressive performance across
various reasoning tasks. However, even state-of-the-art LLMs such as ChatGPT
are prone to logical errors during their reasoning processes. Existing
solutions, such as deploying task-specific verifiers or voting over multiple
reasoning paths, either require extensive human annotations or fail in
scenarios with inconsistent responses. To address these challenges, we
introduce RankPrompt, a new prompting method that enables LLMs to self-rank
their responses without additional resources. RankPrompt breaks down the
ranking problem into a series of comparisons among diverse responses,
leveraging the inherent capabilities of LLMs to generate chains of comparison
as contextual exemplars. Our experiments across 11 arithmetic and commonsense
reasoning tasks show that RankPrompt significantly enhances the reasoning
performance of ChatGPT and GPT-4, with improvements of up to 13%. Moreover,
RankPrompt excels in LLM-based automatic evaluations for open-ended tasks,
aligning with human judgments 74% of the time in the AlpacaEval dataset. It
also exhibits robustness to variations in response order and consistency.
Collectively, our results validate RankPrompt as an effective method for
eliciting high-quality feedback from language models.

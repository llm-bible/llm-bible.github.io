---
layout: publication
title: 'From Single To Multi: How Llms Hallucinate In Multi-document Summarization'
authors: Catarina G. Belem, Pouya Pezeshkpour, Hayate Iso, Seiji Maekawa, Nikita Bhutani, Estevam Hruschka
conference: "Arxiv"
year: 2024
bibkey: belem2024from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13961'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning']
---
Although many studies have investigated and reduced hallucinations in large
language models (LLMs) for single-document tasks, research on hallucination in
multi-document summarization (MDS) tasks remains largely unexplored.
Specifically, it is unclear how the challenges arising from handling multiple
documents (e.g., repetition and diversity of information) affect models
outputs. In this work, we investigate how hallucinations manifest in LLMs when
summarizing topic-specific information from multiple documents. Since no
benchmarks exist for investigating hallucinations in MDS, we use existing news
and conversation datasets, annotated with topic-specific insights, to create
two novel multi-document benchmarks. When evaluating 5 LLMs on our benchmarks,
we observe that on average, up to 75% of the content in LLM-generated summary
is hallucinated, with hallucinations more likely to occur towards the end of
the summaries. Moreover, when summarizing non-existent topic-related
information, gpt-3.5-turbo and GPT-4o still generate summaries about 79.35% and
44% of the time, raising concerns about their tendency to fabricate content. To
understand the characteristics of these hallucinations, we manually evaluate
700+ insights and find that most errors stem from either failing to follow
instructions or producing overly generic insights. Motivated by these
observations, we investigate the efficacy of simple post-hoc baselines in
mitigating hallucinations but find them only moderately effective. Our results
underscore the need for more effective approaches to systematically mitigate
hallucinations in MDS. We release our dataset and code at
github.com/megagonlabs/Hallucination_MDS.

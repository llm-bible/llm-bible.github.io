---
layout: publication
title: 'Ftii-bench: A Comprehensive Multimodal Benchmark For Flow Text With Image Insertion'
authors: Jiacheng Ruan, Yebin Yang, Zehao Lin, Yuchen Feng, Feiyu Xiong, Zeyun Tang, Zhiyu Li
conference: "Arxiv"
year: 2024
bibkey: ruan2024ftii
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12564"}
tags: ['Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT']
---
Benefiting from the revolutionary advances in large language models (LLMs)
and foundational vision models, large vision-language models (LVLMs) have also
made significant progress. However, current benchmarks focus on tasks that
evaluating only a single aspect of LVLM capabilities (e.g., recognition,
detection, understanding). These tasks fail to fully demonstrate LVLMs'
potential in complex application scenarios. To comprehensively assess the
performance of existing LVLMs, we propose a more challenging task called the
Flow Text with Image Insertion task (FTII). This task requires LVLMs to
simultaneously possess outstanding abilities in image comprehension,
instruction understanding, and long-text interpretation. Specifically, given
several text paragraphs and a set of candidate images, as the text paragraphs
accumulate, the LVLMs are required to select the most suitable image from the
candidates to insert after the corresponding paragraph. Constructing a
benchmark for such a task is highly challenging, particularly in determining
the sequence of flowing text and images. To address this challenge, we turn to
professional news reports, which naturally contain a gold standard for
image-text sequences. Based on this, we introduce the Flow Text with Image
Insertion Benchmark (FTII-Bench), which includes 318 high-quality Chinese
image-text news articles and 307 high-quality English image-text news articles,
covering 10 different news domains. Using these 625 high-quality articles, we
construct problems of two different types with multiple levels of difficulty.
Furthermore, we establish two different evaluation pipelines based on the CLIP
model and existing LVLMs. We evaluate 9 open-source and 2 closed-source LVLMs
as well as 2 CLIP-based models. Results indicate that even the most advanced
models (e.g., GPT-4o) face significant challenges when tackling the FTII task.

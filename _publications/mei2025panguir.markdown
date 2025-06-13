---
layout: publication
title: 'Panguir Technical Report For NTCIR-18 AEOLLM Task'
authors: Lang Mei, Chong Chen, Jiaxin Mao
conference: "Arxiv"
year: 2025
bibkey: mei2025panguir
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04809"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'RAG', 'In-Context Learning', 'Prompting', 'Attention Mechanism']
---
As large language models (LLMs) gain widespread attention in both academia
and industry, it becomes increasingly critical and challenging to effectively
evaluate their capabilities. Existing evaluation methods can be broadly
categorized into two types: manual evaluation and automatic evaluation. Manual
evaluation, while comprehensive, is often costly and resource-intensive.
Conversely, automatic evaluation offers greater scalability but is constrained
by the limitations of its evaluation criteria (dominated by reference-based
answers). To address these challenges, NTCIR-18 introduced the AEOLLM
(Automatic Evaluation of LLMs) task, aiming to encourage reference-free
evaluation methods that can overcome the limitations of existing approaches. In
this paper, to enhance the evaluation performance of the AEOLLM task, we
propose three key methods to improve the reference-free evaluation: 1)
Multi-model Collaboration: Leveraging multiple LLMs to approximate human
ratings across various subtasks; 2) Prompt Auto-optimization: Utilizing LLMs to
iteratively refine the initial task prompts based on evaluation feedback from
training samples; and 3) In-context Learning (ICL) Optimization: Based on the
multi-task evaluation feedback, we train a specialized in-context example
retrieval model, combined with a semantic relevance retrieval model, to jointly
identify the most effective in-context learning examples. Experiments conducted
on the final dataset demonstrate that our approach achieves superior
performance on the AEOLLM task.

---
layout: publication
title: 'Supervised Chain Of Thought'
authors: Xiang Zhang, Dujian Ding
conference: "Arxiv"
year: 2024
bibkey: zhang2024supervised
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14198'}
tags: ['Prompting', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Large Language Models (LLMs) have revolutionized natural language processing
and hold immense potential for advancing Artificial Intelligence. However, the
core architecture of most mainstream LLMs -- the Transformer -- has inherent
limitations in computational depth, rendering them theoretically incapable of
solving many reasoning tasks that demand increasingly deep computations. Chain
of Thought (CoT) prompting has emerged as a technique to address these
architectural limitations, as evidenced by several theoretical studies. It
offers a promising approach to solving complex reasoning tasks that were
previously beyond the capabilities of these models. Despite its successes, CoT
and its variants (such as Tree of Thought, Graph of Thought, etc.) rely on a
"one-prompt-for-all" approach, using a single prompt structure (e.g., "think
step by step") for a wide range of tasks -- from counting and sorting to
solving mathematical and algorithmic problems. This approach poses significant
challenges for models to generate the correct reasoning steps, as the model
must navigate through a vast prompt template space to find the appropriate
template for each task. In this work, we build upon previous theoretical
analyses of CoT to demonstrate how the one-prompt-for-all approach can
negatively affect the computability of LLMs. We partition the solution search
space into two: the prompt space and the answer space. Our findings show that
task-specific supervision is essential for navigating the prompt space
accurately and achieving optimal performance. Through experiments with
state-of-the-art LLMs, we reveal a gap in reasoning performance when
supervision is applied versus when it is not.

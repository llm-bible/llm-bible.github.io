---
layout: publication
title: 'A Large-scale Class-level Benchmark Dataset For Code Generation With Llms'
authors: Musfiqur Rahman, Sayedhassan Khatoonabadi, Emad Shihab
conference: "Arxiv"
year: 2025
bibkey: rahman2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15564"}
tags: ['GPT', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Recent advancements in large language models (LLMs) have demonstrated
promising capabilities in code generation tasks. However, most existing
benchmarks focus on isolated functions and fail to capture the complexity of
real-world, class-level software structures. To address this gap, we introduce
a large-scale, Python class-level dataset curated from \\(13\{,\}174\\) real-world
open-source projects. The dataset contains over 842,000 class skeletons, each
including class and method signatures, along with associated docstrings when
available. We preserve structural and contextual dependencies critical to
realistic software development scenarios and enrich the dataset with static
code metrics to support downstream analysis. To evaluate the usefulness of this
dataset, we use extracted class skeletons as prompts for GPT-4 to generate full
class implementations. Results show that the LLM-generated classes exhibit
strong lexical and structural similarity to human-written counterparts, with
average ROUGE@L, BLEU, and TSED scores of 0.80, 0.59, and 0.73, respectively.
These findings confirm that well-structured prompts derived from real-world
class skeletons significantly enhance LLM performance in class-level code
generation. This dataset offers a valuable resource for benchmarking, training,
and improving LLMs in realistic software engineering contexts.

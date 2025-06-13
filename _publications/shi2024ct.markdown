---
layout: publication
title: 'Ct-eval: Benchmarking Chinese Text-to-table Performance In Large Language Models'
authors: Haoxiang Shi, Jiaan Wang, Jiarong Xu, Cen Wang, Tetsuya Sakai
conference: "Arxiv"
year: 2024
bibkey: shi2024ct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12174"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
Text-to-Table aims to generate structured tables to convey the key
information from unstructured documents. Existing text-to-table datasets are
typically oriented English, limiting the research in non-English languages.
Meanwhile, the emergence of large language models (LLMs) has shown great
success as general task solvers in multi-lingual settings (e.g., ChatGPT),
theoretically enabling text-to-table in other languages. In this paper, we
propose a Chinese text-to-table dataset, CT-Eval, to benchmark LLMs on this
task. Our preliminary analysis of English text-to-table datasets highlights two
key factors for dataset construction: data diversity and data hallucination.
Inspired by this, the CT-Eval dataset selects a popular Chinese
multidisciplinary online encyclopedia as the source and covers 28 domains to
ensure data diversity. To minimize data hallucination, we first train an LLM to
judge and filter out the task samples with hallucination, then employ human
annotators to clean the hallucinations in the validation and testing sets.
After this process, CT-Eval contains 88.6K task samples. Using CT-Eval, we
evaluate the performance of open-source and closed-source LLMs. Our results
reveal that zero-shot LLMs (including GPT-4) still have a significant
performance gap compared with human judgment. Furthermore, after fine-tuning,
open-source LLMs can significantly improve their text-to-table ability,
outperforming GPT-4 by a large margin. In short, CT-Eval not only helps
researchers evaluate and quickly understand the Chinese text-to-table ability
of existing LLMs but also serves as a valuable resource to significantly
improve the text-to-table performance of LLMs.

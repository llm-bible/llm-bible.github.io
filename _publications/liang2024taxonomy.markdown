---
layout: publication
title: 'Taxonomy-guided Zero-shot Recommendations With Llms'
authors: Yueqing Liang, Liangwei Yang, Chen Wang, Xiongxiao Xu, Philip S. Yu, Kai Shu
conference: "Arxiv"
year: 2024
bibkey: liang2024taxonomy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14043"}
  - {name: "Code", url: "https://github.com/yueqingliang1/TaxRec"}
tags: ['Fine-Tuning', 'Tools', 'Training Techniques', 'RecSys', 'Has Code', 'Pretraining Methods', 'Prompting']
---
With the emergence of large language models (LLMs) and their ability to
perform a variety of tasks, their application in recommender systems (RecSys)
has shown promise. However, we are facing significant challenges when deploying
LLMs into RecSys, such as limited prompt length, unstructured item information,
and un-constrained generation of recommendations, leading to sub-optimal
performance. To address these issues, we propose a novel method using a
taxonomy dictionary. This method provides a systematic framework for
categorizing and organizing items, improving the clarity and structure of item
information. By incorporating the taxonomy dictionary into LLM prompts, we
achieve efficient token utilization and controlled feature generation, leading
to more accurate and contextually relevant recommendations. Our Taxonomy-guided
Recommendation (TaxRec) approach features a two-step process: one-time taxonomy
categorization and LLM-based recommendation, enabling zero-shot recommendations
without the need for domain-specific fine-tuning. Experimental results
demonstrate TaxRec significantly enhances recommendation quality compared to
traditional zero-shot approaches, showcasing its efficacy as personal
recommender with LLMs. Code is available at
https://github.com/yueqingliang1/TaxRec.

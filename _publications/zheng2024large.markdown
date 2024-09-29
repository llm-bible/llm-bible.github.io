---
layout: publication
title: Large Language Models As Reliable Knowledge Bases?
authors: Zheng Danna, Lapata Mirella, Pan Jeff Z.
conference: "Arxiv"
year: 2024
bibkey: zheng2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.13578"}
tags: ['Fine Tuning', 'GPT', 'In Context Learning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Training Techniques']
---
The NLP community has recently shown a growing interest in leveraging Large Language Models (LLMs) for knowledge-intensive tasks viewing LLMs as potential knowledge bases (KBs). However the reliability and extent to which LLMs can function as KBs remain underexplored. While previous studies suggest LLMs can encode knowledge within their parameters the amount of parametric knowledge alone is not sufficient to evaluate their effectiveness as KBs. This study defines criteria that a reliable LLM-as-KB should meet focusing on factuality and consistency and covering both seen and unseen knowledge. We develop several metrics based on these criteria and use them to evaluate 26 popular LLMs while providing a comprehensive analysis of the effects of model size instruction tuning and in-context learning (ICL). Our results paint a worrying picture. Even a high-performant model like GPT-3.5-turbo is not factual or consistent and strategies like ICL and fine-tuning are unsuccessful at making LLMs better KBs.

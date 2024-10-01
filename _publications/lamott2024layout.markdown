---
layout: publication
title: 'Lapdoc: Layout-aware Prompting For Documents'
authors: Lamott Marcel, Weweler Yves-noel, Ulges Adrian, Shafait Faisal, Krechel Dirk, Obradovic Darko
conference: "Arxiv"
year: 2024
bibkey: lamott2024layout
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09841"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
'Recent advances in training large language models (LLMs) using massive amounts of solely textual data lead to strong generalization across many domains and tasks, including document-specific tasks. Opposed to that there is a trend to train multi-modal transformer architectures tailored for document understanding that are designed specifically to fuse textual inputs with the corresponding document layout. This involves a separate fine-tuning step for which additional training data is required. At present, no document transformers with comparable generalization to LLMs are available That raises the question which type of model is to be preferred for document understanding tasks. In this paper we investigate the possibility to use purely text-based LLMs for document-specific tasks by using layout enrichment. We explore drop-in modifications and rule-based methods to enrich purely textual LLM prompts with layout information. In our experiments we investigate the effects on the commercial ChatGPT model and the open-source LLM Solar. We demonstrate that using our approach both LLMs show improved performance on various standard document benchmarks. In addition, we study the impact of noisy OCR and layout errors, as well as the limitations of LLMs when it comes to utilizing document layout. Our results indicate that layout enrichment can improve the performance of purely text-based LLMs for document understanding by up to 15&#37; compared to just using plain document text. In conclusion, this approach should be considered for the best model choice between text-based LLM or multi-modal document transformers.'

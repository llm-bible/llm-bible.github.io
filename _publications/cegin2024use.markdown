---
layout: publication
title: 'Use Random Selection For Now: Investigation Of Few-shot Selection Strategies In Llm-based Text Augmentation For Classification'
authors: Jan Cegin, Branislav Pecher, Jakub Simko, Ivan Srba, Maria Bielikova, Peter Brusilovsky
conference: "Arxiv"
year: 2024
bibkey: cegin2024use
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10756"}
tags: ['Training Techniques', 'Few-Shot', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
The generative large language models (LLMs) are increasingly used for data
augmentation tasks, where text samples are paraphrased (or generated anew) and
then used for classifier fine-tuning. Existing works on augmentation leverage
the few-shot scenarios, where samples are given to LLMs as part of prompts,
leading to better augmentations. Yet, the samples are mostly selected randomly
and a comprehensive overview of the effects of other (more ``informed'') sample
selection strategies is lacking. In this work, we compare sample selection
strategies existing in few-shot learning literature and investigate their
effects in LLM-based textual augmentation. We evaluate this on in-distribution
and out-of-distribution classifier performance. Results indicate, that while
some ``informed'' selection strategies increase the performance of models,
especially for out-of-distribution data, it happens only seldom and with
marginal performance increases. Unless further advances are made, a default of
random sample selection remains a good option for augmentation practitioners.

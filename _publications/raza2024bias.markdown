---
layout: publication
title: 'Beads: Bias Evaluation Across Domains'
authors: Raza Shaina, Rahman Mizanur, Zhang Michael R.
conference: "Arxiv"
year: 2024
bibkey: raza2024bias
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04220"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
Recent advancements in large language models (LLMs) have greatly enhanced natural language processing (NLP) applications. Nevertheless, these models often inherit biases from their training data. Despite the availability of various datasets, most are limited to one or two NLP tasks (typically classification or evaluation) and lack comprehensive evaluations across a broader range of NLP tasks. To address this gap, we introduce the Bias Evaluations Across Domains (BEADs) dataset, designed to support a wide array of NLP tasks, including text classification, token classification, bias quantification, and benign language generation. A key focus of this paper is the gold label subset of BEADs, an important portion of the data verified by experts to ensure high reliability. BEADs provides data for both fine-tuning, including classification and language generation tasks, and for evaluating LLMs. Our findings indicate that BEADs effectively identifies numerous biases when fine-tuned on this dataset. It also reduces biases when used for fine-tuning language generation task, while preserving language quality. The results also reveal some prevalent demographic biases in LLMs when BEADs is used for evaluation in demographic task. The benchmarking results highlight the efficacy of fine-tuning LLMs for bias identification and the necessity of comprehensive bias evaluation. We make BEADs publicly available to promote more responsible AI development. The dataset can be accessed at https://huggingface.co/datasets/shainar/BEAD .

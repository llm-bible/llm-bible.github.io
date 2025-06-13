---
layout: publication
title: 'Control LLM: Controlled Evolution For Intelligence Retention In LLM'
authors: Haichao Wei, Yunxiang Ren, Zhoutong Fu, Aman Lunia, Yi-lin Chen, Alice Leung, Ya Xu
conference: "Arxiv"
year: 2025
bibkey: wei2025control
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.10979"}
  - {name: "Code", url: "https://github.com/linkedin/ControlLLM)"}
  - {name: "Code", url: "https://huggingface.co/ControlLLM)"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Large Language Models (LLMs) demand significant computational resources,
making it essential to enhance their capabilities without retraining from
scratch. A key challenge in this domain is \textit\{catastrophic forgetting\}
(CF), which hampers performance during Continuous Pre-training (CPT) and
Continuous Supervised Fine-Tuning (CSFT). We propose \textbf\{Control LLM\}, a
novel approach that leverages parallel pre-trained and expanded transformer
blocks, aligning their hidden-states through interpolation strategies This
method effectively preserves performance on existing tasks while seamlessly
integrating new knowledge.
  Extensive experiments demonstrate the effectiveness of Control LLM in both
CPT and CSFT. On Llama3.1-8B-Instruct, it achieves significant improvements in
mathematical reasoning (\\(+14.4%\\) on Math-Hard) and coding performance (\\(+10%\\)
on MBPP-PLUS). On Llama3.1-8B, it enhances multilingual capabilities (\\(+10.6%\\)
on C-Eval, \\(+6.8%\\) on CMMLU, and \\(+30.2%\\) on CMMLU-0shot-CoT). It surpasses
existing methods and achieves SOTA among open-source models tuned from the same
base model, using substantially less data and compute. Crucially, these gains
are realized while preserving strong original capabilities, with minimal
degradation (\\(<4.3% \text\{on MMLU\}\\)) compared to \\(>35%\\) in open-source Math
and Coding models. This approach has been successfully deployed in LinkedIn's
GenAI-powered job seeker and Ads unit products.
  To support further research, we release the training and evaluation code
(https://github.com/linkedin/ControlLLM) along with models trained on public
datasets (https://huggingface.co/ControlLLM) to the community.

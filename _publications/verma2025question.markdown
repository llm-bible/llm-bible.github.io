---
layout: publication
title: 'Moemoe: Question Guided Dense And Scalable Sparse Mixture-of-expert For Multi-source Multi-modal Answering'
authors: Vinay Kumar Verma, Shreyas Sunil Kulkarni, Happy Mittal, Deepak Gupta
conference: "Arxiv"
year: 2025
bibkey: verma2025question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.06296"}
tags: ['Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Transformer', 'Applications', 'Attention Mechanism']
---
Question Answering (QA) and Visual Question Answering (VQA) are well-studied
problems in the language and vision domain. One challenging scenario involves
multiple sources of information, each of a different modality, where the answer
to the question may exist in one or more sources. This scenario contains richer
information but is highly complex to handle. In this work, we formulate a novel
question-answer generation (QAG) framework in an environment containing
multi-source, multimodal information. The answer may belong to any or all
sources; therefore, selecting the most prominent answer source or an optimal
combination of all sources for a given question is challenging. To address this
issue, we propose a question-guided attention mechanism that learns attention
across multiple sources and decodes this information for robust and unbiased
answer generation. To learn attention within each source, we introduce an
explicit alignment between questions and various information sources, which
facilitates identifying the most pertinent parts of the source information
relative to the question. Scalability in handling diverse questions poses a
challenge. We address this by extending our model to a sparse
mixture-of-experts (sparse-MoE) framework, enabling it to handle thousands of
question types. Experiments on T5 and Flan-T5 using three datasets demonstrate
the model's efficacy, supported by ablation studies.

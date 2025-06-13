---
layout: publication
title: 'Enhancing Auto-regressive Chain-of-thought Through Loop-aligned Reasoning'
authors: Qifan Yu, Zhenyu He, Sijie Li, Xun Zhou, Jun Zhang, Jingjing Xu, Di He
conference: "Arxiv"
year: 2025
bibkey: yu2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08482"}
  - {name: "Code", url: "https://github.com/qifanyu/RELAY"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Has Code', 'Prompting']
---
Chain-of-Thought (CoT) prompting has emerged as a powerful technique for
enhancing language model's reasoning capabilities. However, generating long and
correct CoT trajectories is challenging. Recent studies have demonstrated that
Looped Transformers possess remarkable length generalization capabilities, but
their limited generality and adaptability prevent them from serving as an
alternative to auto-regressive solutions. To better leverage the strengths of
Looped Transformers, we propose RELAY (REasoning through Loop Alignment
iterativelY). Specifically, we align the steps of Chain-of-Thought (CoT)
reasoning with loop iterations and apply intermediate supervision during the
training of Looped Transformers. This additional iteration-wise supervision not
only preserves the Looped Transformer's ability for length generalization but
also enables it to predict CoT reasoning steps for unseen data. Therefore, we
leverage this Looped Transformer to generate accurate reasoning chains for
complex problems that exceed the training length, which will then be used to
fine-tune an auto-regressive model. We conduct extensive experiments, and the
results demonstrate the effectiveness of our approach, with significant
improvements in the performance of the auto-regressive model. Code will be
released at https://github.com/qifanyu/RELAY.

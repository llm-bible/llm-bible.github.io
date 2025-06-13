---
layout: publication
title: 'Model Tells Itself Where To Attend: Faithfulness Meets Automatic Attention Steering'
authors: Qingru Zhang, Xiaodong Yu, Chandan Singh, Xiaodong Liu, Liyuan Liu, Jianfeng Gao, Tuo Zhao, Dan Roth, Hao Cheng
conference: "Arxiv"
year: 2024
bibkey: zhang2024model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.10790"}
  - {name: "Code", url: "https://github.com/QingruZhang/AutoPASTA"}
tags: ['RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Has Code', 'Prompting']
---
Large language models (LLMs) have demonstrated remarkable performance across
various real-world tasks. However, they often struggle to fully comprehend and
effectively utilize their input contexts, resulting in responses that are
unfaithful or hallucinated. This difficulty increases for contexts that are
long or contain distracting information, which can divert LLMs from fully
capturing essential evidence. To address this issue, many works use prompting
to help LLMs utilize contextual information more faithfully. For instance,
iterative prompting highlights key information in two steps that first ask the
LLM to identify important pieces of context and then derive answers
accordingly. However, prompting methods are constrained to highlighting key
information implicitly in token space, which is often insufficient to fully
steer the model's attention. To improve model faithfulness more reliably, we
propose AutoPASTA, a method that automatically identifies key contextual
information and explicitly highlights it by steering an LLM's attention scores.
Like prompting, AutoPASTA is applied at inference time and does not require
changing any model parameters. Our experiments on open-book QA demonstrate that
AutoPASTA effectively enables models to grasp essential contextual information,
leading to substantially improved model faithfulness and performance, e.g., an
average improvement of 7.95% for LLAMA3-70B-Instruct. Code will be publicly
available at https://github.com/QingruZhang/AutoPASTA .

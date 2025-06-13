---
layout: publication
title: 'Eliciting In-context Retrieval And Reasoning For Long-context Large Language Models'
authors: Yifu Qiu, Varun Embar, Yizhe Zhang, Navdeep Jaitly, Shay B. Cohen, Benjamin Han
conference: "Arxiv"
year: 2025
bibkey: qiu2025eliciting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.08248'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advancements in long-context language models (LCLMs) promise to
transform Retrieval-Augmented Generation (RAG) by simplifying pipelines. With
their expanded context windows, LCLMs can process entire knowledge bases and
perform retrieval and reasoning directly -- a capability we define as
In-Context Retrieval and Reasoning (ICR^2). However, existing benchmarks like
LOFT often overestimate LCLM performance by providing overly simplified
contexts. To address this, we introduce ICR^2, a benchmark that evaluates LCLMs
in more realistic scenarios by including confounding passages retrieved with
strong retrievers. We then propose three methods to enhance LCLM performance:
(1) retrieve-then-generate fine-tuning, (2) retrieval-attention-probing, which
uses attention heads to filter and de-noise long contexts during decoding, and
(3) joint retrieval head training alongside the generation head. Our evaluation
of five well-known LCLMs on LOFT and ICR^2 demonstrates significant gains with
our best approach applied to Mistral-7B: +17 and +15 points by Exact Match on
LOFT, and +13 and +2 points on ICR^2, compared to vanilla RAG and supervised
fine-tuning, respectively. It even outperforms GPT-4-Turbo on most tasks
despite being a much smaller model.

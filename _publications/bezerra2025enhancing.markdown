---
layout: publication
title: 'Llmquoter: Enhancing RAG Capabilities Through Efficient Quote Extraction From Large Contexts'
authors: Yuri Facanha Bezerra, Li Weigang
conference: "Arxiv"
year: 2025
bibkey: bezerra2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.05554'}
tags: ['RAG', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
We introduce LLMQuoter, a lightweight, distillation-based model designed to
enhance Retrieval Augmented Generation (RAG) by extracting the most relevant
textual evidence for downstream reasoning tasks. Built on the LLaMA-3B
architecture and fine-tuned with Low-Rank Adaptation (LoRA) on a 15,000-sample
subset of HotpotQA, LLMQuoter adopts a "quote-first-then-answer" strategy,
efficiently identifying key quotes before passing curated snippets to reasoning
models. This workflow reduces cognitive overhead and outperforms full-context
approaches like Retrieval-Augmented Fine-Tuning (RAFT), achieving over 20-point
accuracy gains across both small and large language models. By leveraging
knowledge distillation from a high-performing teacher model, LLMQuoter achieves
competitive results in a resource-efficient fine-tuning setup. It democratizes
advanced RAG capabilities, delivering significant performance improvements
without requiring extensive model retraining. Our results highlight the
potential of distilled quote-based reasoning to streamline complex workflows,
offering a scalable and practical solution for researchers and practitioners
alike.

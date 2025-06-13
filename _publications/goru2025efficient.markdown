---
layout: publication
title: 'Efficient Single-pass Training For Multi-turn Reasoning'
authors: Ritesh Goru, Shanay Mehta, Prateek Jain
conference: "Arxiv"
year: 2025
bibkey: goru2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18246"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Training Large Language Models ( LLMs) to generate explicit reasoning before
they produce an answer has been shown to improve their performance across
various tasks such as mathematics and coding. However, fine-tuning LLMs on
multi-turn reasoning datasets presents a unique challenge: LLMs must generate
reasoning tokens that are excluded from subsequent inputs to the LLM. This
discrepancy prevents us from processing an entire conversation in a single
forward pass-an optimization readily available when we fine-tune on a
multi-turn non-reasoning dataset. This paper proposes a novel approach that
overcomes this limitation through response token duplication and a custom
attention mask that enforces appropriate visibility constraints. Our approach
significantly reduces the training time and allows efficient fine-tuning on
multi-turn reasoning datasets.

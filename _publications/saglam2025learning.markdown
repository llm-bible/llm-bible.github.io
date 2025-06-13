---
layout: publication
title: 'Learning Task Representations From In-context Learning'
authors: Baturay Saglam, Zhuoran Yang, Dionysis Kalogerias, Amin Karbasi
conference: "Arxiv"
year: 2025
bibkey: saglam2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.05390"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have demonstrated remarkable proficiency in
in-context learning (ICL), where models adapt to new tasks through
example-based prompts without requiring parameter updates. However,
understanding how tasks are internally encoded and generalized remains a
challenge. To address some of the empirical and technical gaps in the
literature, we introduce an automated formulation for encoding task information
in ICL prompts as a function of attention heads within the transformer
architecture. This approach computes a single task vector as a weighted sum of
attention heads, with the weights optimized causally via gradient descent. Our
findings show that existing methods fail to generalize effectively to
modalities beyond text. In response, we also design a benchmark to evaluate
whether a task vector can preserve task fidelity in functional regression
tasks. The proposed method successfully extracts task-specific information from
in-context demonstrations and excels in both text and regression tasks,
demonstrating its generalizability across modalities. Moreover, ablation
studies show that our method's effectiveness stems from aligning the
distribution of the last hidden state with that of an optimally performing
in-context-learned model.

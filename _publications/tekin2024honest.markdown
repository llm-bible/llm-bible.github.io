---
layout: publication
title: '\(h^3\)fusion: Helpful, Harmless, Honest Fusion Of Aligned Llms'
authors: Selim Furkan Tekin, Fatih Ilhan, Tiansheng Huang, Sihao Hu, Zachary Yahn, Ling Liu
conference: "Arxiv"
year: 2024
bibkey: tekin2024honest
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17792"}
tags: ['Fine-Tuning', 'RAG', 'Model Architecture', 'Merging', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Alignment of pretrained LLMs using instruction-based datasets is critical for
creating fine-tuned models that reflect human preference. A growing number of
alignment-based fine-tuning algorithms and benchmarks emerged recently, fueling
the efforts on effective alignments of pre-trained LLMs to ensure helpful,
harmless, and honest answers from both open-source and closed-source LLMs. This
paper tackles this problem by developing an alignment fusion approach, coined
as \\(H^3\\)Fusion, with three unique characteristics. First, \\(H^3\\)Fusion ensembles
multiple individually aligned LLMs to create a final fine-tuned alignment model
with enhanced capabilities beyond those of individual models, delivering robust
alignment through promoting helpful, harmless, honest fusion. Second,
\\(H^3\\)Fusion leverages the mixture-of-experts (MoE) methodology in two steps. We
first freeze the multi-head attention weights of each individual model while
tuning the FFN layer during alignment fusion. Then we merge the aligned model
weights with an expert router according to the type of input instruction and
dynamically select a subset of experts that are best suited for producing the
output response. Finally, we boost the performance of the resulting
\\(H^3\\)3Fusion model by introducing gating loss and regularization terms. The
former penalizes the selection errors of the expert-router, and the latter
mediates the expert weights drifting during fine-tuning and dynamically adjusts
the fusion behavior of the resulting model by canalizing the activations on the
experts. Extensive evaluations on three benchmark datasets show that
\\(H^3\\)3Fusion is more helpful, less harmful, and more honest from two aspects:
it outperforms each individually aligned model by \\(11.37%\\), and it provides
stronger robustness compared to the state-of-the-art LLM ensemble approaches by
\\(13.77%\\). Code is available at github.com/sftekin/h3fusion.

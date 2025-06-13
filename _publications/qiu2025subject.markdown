---
layout: publication
title: 'Mindllm: A Subject-agnostic And Versatile Model For Fmri-to-text Decoding'
authors: Weikang Qiu, Zheng Huang, Haoyu Hu, Aosong Feng, Yujun Yan, Rex Ying
conference: "Arxiv"
year: 2025
bibkey: qiu2025subject
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15786"}
tags: ['Model Architecture', 'Transformer', 'Attention Mechanism']
---
Decoding functional magnetic resonance imaging (fMRI) signals into text has
been a key challenge in the neuroscience community, with the potential to
advance brain-computer interfaces and uncover deeper insights into brain
mechanisms. However, existing approaches often struggle with suboptimal
predictive performance, limited task variety, and poor generalization across
subjects. In response to this, we propose MindLLM, a model designed for
subject-agnostic and versatile fMRI-to-text decoding. MindLLM consists of an
fMRI encoder and an off-the-shelf LLM. The fMRI encoder employs a
neuroscience-informed attention mechanism, which is capable of accommodating
subjects with varying input shapes and thus achieves high-performance
subject-agnostic decoding. Moreover, we introduce Brain Instruction Tuning
(BIT), a novel approach that enhances the model's ability to capture diverse
semantic representations from fMRI signals, facilitating more versatile
decoding. We evaluate MindLLM on comprehensive fMRI-to-text benchmarks. Results
demonstrate that our model outperforms the baselines, improving downstream
tasks by 12.0%, unseen subject generalization by 16.4%, and novel task
adaptation by 25.0%. Furthermore, the attention patterns in MindLLM provide
interpretable insights into its decision-making process.

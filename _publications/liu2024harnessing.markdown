---
layout: publication
title: 'Harnessing Large Language Models For Multimodal Product Bundling'
authors: Liu Xiaohao, Wu Jie, Tao Zhulin, Ma Yunshan, Wei Yinwei, Chua Tat-seng
conference: "Arxiv"
year: 2024
bibkey: liu2024harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11712"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Merging', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Tokenization']
---
Product bundling provides clients with a strategic combination of individual
items. And it has gained significant attention in recent years as a fundamental
prerequisite for online services. Recent methods utilize multimodal information
through sophisticated extractors for bundling, but remain limited by inferior
semantic understanding, the restricted scope of knowledge, and an inability to
handle cold-start issues. Despite the extensive knowledge and complex reasoning
capabilities of large language models (LLMs), their direct utilization fails to
process multimodalities and exploit their knowledge for multimodal product
bundling. Adapting LLMs for this purpose involves demonstrating the synergies
among different modalities and designing an effective optimization strategy for
bundling, which remains challenging. To this end, we introduce Bundle-LLM to
bridge the gap between LLMs and product bundling tasks. Specifically, we
utilize a hybrid item tokenization to integrate multimodal information, where a
simple yet powerful multimodal fusion module followed by a trainable projector
embeds all non-textual features into a single token. This module not only
explicitly exhibits the interplays among modalities but also shortens the
prompt length, thereby boosting efficiency. By designing a prompt template, we
formulate product bundling as a multiple-choice question given candidate items.
Furthermore, we adopt progressive optimization strategy to fine-tune the LLMs
for disentangled objectives, achieving effective product bundling capability
with comprehensive multimodal semantic understanding. Extensive experiments on
four datasets from two application domains show that our approach outperforms a
range of state-of-the-art (SOTA) methods.

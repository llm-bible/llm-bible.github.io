---
layout: publication
title: 'Expediting And Elevating Large Language Model Reasoning Via Hidden Chain-of-thought Decoding'
authors: Tianqiao Liu, Zui Chen, Zitao Liu, Mi Tian, Weiqi Luo
conference: "Arxiv"
year: 2024
bibkey: liu2024expediting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.08561'}
tags: ['Agentic', 'Training Techniques', 'Applications', 'Prompting', 'Pretraining Methods']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
tasks requiring reasoning and multi-step problem-solving through the use of
chain-of-thought (CoT) prompting. However, generating the full CoT process
results in significantly longer output sequences, leading to increased
computational costs and latency during inference. To address this challenge, we
propose a novel approach to compress the CoT process through semantic
alignment, enabling more efficient decoding while preserving the benefits of
CoT reasoning. Our method introduces an auxiliary CoT model that learns to
generate and compress the full thought process into a compact special token
representation semantically aligned with the original CoT output. This
compressed representation is then integrated into the input of the Hidden
Chain-of-Thought (HCoT) model. The training process follows a two-stage
procedure: First, the CoT model is optimized to generate the compressed token
representations aligned with the ground-truth CoT outputs using a contrastive
loss. Subsequently, with the CoT model parameters frozen, the HCoT model is
fine-tuned to generate accurate subsequent predictions conditioned on the
prefix instruction and the compressed CoT representations from the CoT model.
Extensive experiments across three challenging domains - mathematical
reasoning, agent invocation, and question answering - demonstrate that our
semantic compression approach achieves competitive or improved performance
compared to the full CoT baseline, while providing significant speedups of at
least 1.5x in decoding time. Moreover, incorporating contrastive learning
objectives further enhances the quality of the compressed representations,
leading to better CoT prompting and improved task accuracy. Our work paves the
way for more efficient exploitation of multi-step reasoning capabilities in
LLMs across a wide range of applications.

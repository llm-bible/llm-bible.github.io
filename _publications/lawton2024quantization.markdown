---
layout: publication
title: 'Quailora: Quantization-aware Initialization For Lora'
authors: Neal Lawton, Aishwarya Padmakumar, Judith Gaspers, Jack Fitzgerald, Anoop Kumar, Greg Ver Steeg, Aram Galstyan
conference: "Arxiv"
year: 2024
bibkey: lawton2024quantization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14713"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Quantization', 'Pretraining Methods', 'Fine-Tuning']
---
QLoRA reduces the memory-cost of fine-tuning a large language model (LLM)
with LoRA by quantizing the base LLM. However, quantization introduces
quantization errors that negatively impact model performance after fine-tuning.
In this paper we introduce QuAILoRA, a quantization-aware initialization for
LoRA that mitigates this negative impact by decreasing quantization errors at
initialization. Our method spends a small amount of computational overhead to
compute this quantization-aware initialization, without increasing the
memory-cost of fine-tuning. We evaluate our method on several causal language
modeling and downstream evaluation tasks using several different model sizes
and families. We observe that almost all LLMs fined-tuned with QuAILoRA achieve
better validation perplexity. When evaluated on downstream tasks, we find that
QuAILoRA yields improvements proportional to the negative effect of
quantization error. On average, applying QuAILoRA to 4-bit QLoRA models yields
75% of the validation perplexity decrease and 86% of the downstream task
accuracy increase as doubling the quantization precision to 8-bit, without
increasing GPU memory utilization during fine-tuning.

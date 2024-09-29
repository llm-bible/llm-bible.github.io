---
layout: publication
title: ApiQ Finetuning of 2-Bit Quantized Large Language Model
authors: Liao Baohao, Herold Christian, Khadivi Shahram, Monz Christof
conference: "Arxiv"
year: 2024
bibkey: liao2024apiq
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.05147"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Quantization', 'Tools']
---
Memory-efficient finetuning of large language models (LLMs) has recently attracted huge attention with the increasing size of LLMs primarily due to the constraints posed by GPU memory limitations and the effectiveness of these methods compared to full finetuning. Despite the advancements current strategies for memory-efficient finetuning such as QLoRA exhibit inconsistent performance across diverse bit-width quantizations and multifaceted tasks. This inconsistency largely stems from the detrimental impact of the quantization process on preserved knowledge leading to catastrophic forgetting and undermining the utilization of pretrained models for finetuning purposes. In this work we introduce a novel quantization framework ApiQ designed to restore the lost information from quantization by concurrently initializing the LoRA components and quantizing the weights of LLMs. This approach ensures the maintenance of the original LLMs activation precision while mitigating the error propagation from shallower into deeper layers. Through comprehensive evaluations conducted on a spectrum of language tasks with various LLMs ApiQ demonstrably minimizes activation error during quantization. Consequently it consistently achieves superior finetuning results across various bit-widths.

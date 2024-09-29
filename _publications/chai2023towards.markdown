---
layout: publication
title: INT2.1: Towards Fine-tunable Quantized Large Language Models With Error Correction Through Low-rank Adaptation
authors: Chai Yuji, Gkountouras John, Ko Glenn G., Brooks David, Wei Gu-yeon
conference: "Arxiv"
year: 2023
bibkey: chai2023towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.08162"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques']
---
We introduce a method that dramatically reduces fine-tuning VRAM requirements and rectifies quantization errors in quantized Large Language Models. First we develop an extremely memory-efficient fine-tuning (EMEF) method for quantized models using Low-Rank Adaptation (LoRA) and drawing upon it we construct an error-correcting algorithm designed to minimize errors induced by the quantization process. Our method reduces the memory requirements by up to 5.6 times which enables fine-tuning a 7 billion parameter Large Language Model (LLM) on consumer laptops. At the same time we propose a Low-Rank Error Correction (LREC) method that exploits the added LoRA layers to ameliorate the gap between the quantized model and its float point counterpart. Our error correction framework leads to a fully functional INT2 quantized LLM with the capacity to generate coherent English text. To the best of our knowledge this is the first INT2 Large Language Model that has been able to reach such a performance. The overhead of our method is merely a 1.05 times increase in model size which translates to an effective precision of INT2.1. Also our method readily generalizes to other quantization standards such as INT3 INT4 and INT8 restoring their lost performance which marks a significant milestone in the field of model quantization. The strategies delineated in this paper hold promising implications for the future development and optimization of quantized models marking a pivotal shift in the landscape of low-resource machine learning computations.

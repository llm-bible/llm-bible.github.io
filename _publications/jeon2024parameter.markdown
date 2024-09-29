---
layout: publication
title: L4Q Parameter Efficient Quantization45;aware Fine45;tuning On Large Language Models
authors: Jeon Hyesung, Kim Yulhwa, Kim Jae-joon
conference: "Arxiv"
year: 2024
bibkey: jeon2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04902"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Quantization', 'RAG', 'Training Techniques']
---
Due to the high memory and computational costs associated with Large Language Models model compression via quantization and parameter45;efficient fine45;tuning (PEFT) methods such as low45;rank adaptation (LoRA) are gaining popularity. This has led to active research on quantization45;aware PEFT techniques which aim to create models with high accuracy and low memory overhead. Among quantization methods post45;training quantization (PTQ) is more commonly used in previous works than quantization45;aware training (QAT) despite QATs potential for higher accuracy. This preference is due to PTQs low training overhead. However PTQ45;based PEFT methods often utilize high45;precision parameters making it difficult to fully exploit the efficiency of quantization. Additionally they have limited adaptation ability due to a reduced and constrained LoRA parameter structure. To overcome these challenges we propose L4Q which leverages joint quantization and fine45;tuning to reduce QATs memory overhead and produce models that consist entirely of quantized weights while achieving effective adaptation to downstream tasks. By design L4Q allows quantization parameters to reflect weight updates while weight updates reduce quantization errors. Our experiments demonstrate that this coupled quantization and fine45;tuning approach yields superior accuracy compared to decoupled fine45;tuning schemes in sub45;445;bit quantization. Using the LLaMA model families and instructional datasets we showcase L4Qs capabilities in language tasks and few45;shot in45;context learning.

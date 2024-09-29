---
layout: publication
title: Memory45;efficient Fine45;tuning Of Compressed Large Language Models Via Sub45;445;bit Integer Quantization
authors: Kim Jeonghoon, Lee Jung Hyun, Kim Sungdong, Park Joonsuk, Yoo Kang Min, Kwon Se Jung, Lee Dongsoo
conference: "Arxiv"
year: 2023
bibkey: kim2023memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14152"}
tags: ['Efficiency And Optimization', 'Language Modeling', 'Quantization', 'RAG']
---
Large language models (LLMs) face the challenges in fine45;tuning and deployment due to their high memory demands and computational costs. While parameter45;efficient fine45;tuning (PEFT) methods aim to reduce the memory usage of the optimizer state during fine45;tuning the inherent size of pre45;trained LLM weights continues to be a pressing concern. Even though quantization techniques are widely proposed to ease memory demands and accelerate LLM inference most of these techniques are geared towards the deployment phase. To bridge this gap this paper presents Parameter45;Efficient and Quantization45;aware Adaptation (PEQA) 45; a simple yet effective method that combines the advantages of PEFT with quantized LLMs. By updating solely the quantization scales PEQA can be directly applied to quantized LLMs ensuring seamless task transitions. Parallel to existing PEFT methods PEQA significantly reduces the memory overhead associated with the optimizer state. Furthermore it leverages the advantages of quantization to substantially reduce model sizes. Even after fine45;tuning the quantization structure of a PEQA45;tuned LLM remains intact allowing for accelerated inference on the deployment stage. We employ PEQA45;tuning for task45;specific adaptation on LLMs with up to 65 billion parameters. To assess the logical reasoning and language comprehension of PEQA45;tuned LLMs we fine45;tune low45;bit quantized LLMs using a instruction dataset. Our results show that even when LLMs are quantized to below 445;bit precision their capabilities in language modeling few45;shot in45;context learning and comprehension can be resiliently restored to (or even improved over) their full45;precision original performances with PEQA.

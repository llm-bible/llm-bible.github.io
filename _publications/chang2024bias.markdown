---
layout: publication
title: Bias45;aware Low45;rank Adaptation Mitigating Catastrophic Inheritance Of Large Language Models
authors: Chang Yupeng, Chang Yi, Wu Yuan
conference: "Arxiv"
year: 2024
bibkey: chang2024bias
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04556"}
  - {name: "Code", url: "https://github.com/cyp&#45;jlu&#45;ai/BA&#45;LoRA"}
tags: ['Applications', 'Ethics And Bias', 'Fine Tuning', 'Has Code', 'Training Techniques']
---
Large language models (LLMs) have exhibited remarkable proficiency across a diverse array of natural language processing (NLP) tasks. However adapting LLMs to downstream applications typically necessitates computationally intensive and memory45;demanding fine45;tuning procedures. To mitigate these burdens parameter45;efficient fine45;tuning (PEFT) techniques have emerged as a promising approach to tailor LLMs with minimal computational overhead. While PEFT methods offer substantial advantages they do not fully address the pervasive issue of bias propagation from pre45;training data. In this work we introduce Bias45;Aware Low45;Rank Adaptation (BA45;LoRA) a novel PEFT method designed to counteract bias inheritance. BA45;LoRA incorporates three distinct regularization terms (1) consistency regularizer (2) diversity regularizer and (3) singular vector decomposition regularizer. These regularizers collectively aim to improve the generative models consistency diversity and generalization capabilities during the fine45;tuning process. Through extensive experiments on a variety of natural language understanding (NLU) and natural language generation (NLG) tasks employing prominent LLMs such as LLaMA Mistral and Gemma we demonstrate that BA45;LoRA surpasses the performance of LoRA and its state45;of45;the45;art variants. Moreover our method effectively mitigates the deleterious effects of pre45;training bias leading to more reliable and robust model outputs. The code is available at https://github.com/cyp&#45;jlu&#45;ai/BA&#45;LoRA.

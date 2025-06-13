---
layout: publication
title: 'CROW: Eliminating Backdoors From Large Language Models Via Internal Consistency Regularization'
authors: Nay Myat Min, Long H. Pham, Yige Li, Jun Sun
conference: "Arxiv"
year: 2024
bibkey: min2024eliminating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.12768"}
tags: ['Security', 'Model Architecture', 'Language Modeling', 'RAG', 'Applications']
---
Recent studies reveal that Large Language Models (LLMs) are susceptible to
backdoor attacks, where adversaries embed hidden triggers that manipulate model
responses. Existing backdoor defense methods are primarily designed for vision
or classification tasks, and are thus ineffective for text generation tasks,
leaving LLMs vulnerable. We introduce Internal Consistency Regularization
(CROW), a novel defense using consistency regularization finetuning to address
layer-wise inconsistencies caused by backdoor triggers. CROW leverages the
intuition that clean models exhibit smooth, consistent transitions in hidden
representations across layers, whereas backdoored models show noticeable
fluctuation when triggered. By enforcing internal consistency through
adversarial perturbations and regularization, CROW neutralizes backdoor effects
without requiring clean reference models or prior trigger knowledge, relying
only on a small set of clean data. This makes it practical for deployment
across various LLM architectures. Experimental results demonstrate that CROW
consistently achieves a significant reductions in attack success rates across
diverse backdoor strategies and tasks, including negative sentiment, targeted
refusal, and code injection, on models such as Llama-2 (7B, 13B), CodeLlama
(7B, 13B) and Mistral-7B, while preserving the model's generative capabilities.

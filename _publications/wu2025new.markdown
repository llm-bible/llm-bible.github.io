---
layout: publication
title: 'Automedprompt: A New Framework For Optimizing LLM Medical Prompts Using Textual Gradients'
authors: Sean Wu, Michael Koo, Fabien Scalzo, Ira Kurtz
conference: "Arxiv"
year: 2025
bibkey: wu2025new
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15944"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) have demonstrated increasingly sophisticated
performance in medical and other fields of knowledge. Traditional methods of
creating specialist LLMs require extensive fine-tuning and training of models
on large datasets. Recently, prompt engineering, instead of fine-tuning, has
shown potential to boost the performance of general foundation models. However,
prompting methods such as chain-of-thought (CoT) may not be suitable for all
subspecialty, and k-shot approaches may introduce irrelevant tokens into the
context space. We present AutoMedPrompt, which explores the use of textual
gradients to elicit medically relevant reasoning through system prompt
optimization. AutoMedPrompt leverages TextGrad's automatic differentiation via
text to improve the ability of general foundation LLMs. We evaluated
AutoMedPrompt on Llama 3, an open-source LLM, using several QA benchmarks,
including MedQA, PubMedQA, and the nephrology subspecialty-specific NephSAP.
Our results show that prompting with textual gradients outperforms previous
methods on open-source LLMs and surpasses proprietary models such as GPT-4,
Claude 3 Opus, and Med-PaLM 2. AutoMedPrompt sets a new state-of-the-art (SOTA)
performance on PubMedQA with an accuracy of 82.6\\(%\\), while also outperforming
previous prompting strategies on open-sourced models for MedQA (77.7\\(%\\)) and
NephSAP (63.8\\(%\\)).

---
layout: publication
title: 'Non-instructional Fine-tuning: Enabling Instruction-following Capabilities In Pre-trained Language Models Without Instruction-following Data'
authors: Juncheng Xie, Shensian Syu, Hung-yi Lee
conference: "Arxiv"
year: 2024
bibkey: xie2024non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00096"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Instruction fine-tuning is crucial for today's large language models (LLMs)
to learn to follow instructions and align with human preferences.
Conventionally, supervised data, including the instruction and the correct
response, is required for instruction fine-tuning. To obtain such data, some
researchers prompted well-trained models like GPT-4 to generate instructions
and correct responses. In this paper, we propose a novel approach that uses the
first half of a random text from OpenWebText as the instruction and
GPT-3.5-turbo or GPT-4-turbo to complete the text as the response. Despite the
data being "non-instructional", we found that pre-trained LLMs fine-tuned on
this data can gain instruction-following capabilities. This observation is
verified by fine-tuning several well-known pre-trained LLMs (e.g., LLaMA-2-7B,
LLaMA-3-8B, LLaMA-3-70B, Mistral-7B-v0.1). The "non-instructional data" also
improved some models that underwent supervised fine-tuning and human preference
alignment. Our LLaMA-3-70B-Instruct fine-tuned through "non-instructional data"
is comparable with LLaMA-3.1-70B-Instruct on the Arena Hard leaderboard. We
analyzed the "non-instructional data" and ensured it is devoid of content
related to instruction fine-tuning. Our findings will inspire further
investigation into how to develop instruction-following capabilities without
explicit instruction-related data.

---
layout: publication
title: 'Lora Fine-tuning Efficiently Undoes Safety Training In Llama 2-chat 70B'
authors: Simon Lermen, Charlie Rogers-smith, Jeffrey Ladish
conference: "Arxiv"
year: 2023
bibkey: lermen2023lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20624"}
tags: ['Responsible AI', 'Agentic', 'Security', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning']
---
AI developers often apply safety alignment procedures to prevent the misuse
of their AI systems. For example, before Meta released Llama 2-Chat - a
collection of instruction fine-tuned large language models - they invested
heavily in safety training, incorporating extensive red-teaming and
reinforcement learning from human feedback. We explore the robustness of safety
training in language models by subversively fine-tuning Llama 2-Chat. We employ
quantized low-rank adaptation (LoRA) as an efficient fine-tuning method. With a
budget of less than \$200 and using only one GPU, we successfully undo the
safety training of Llama 2-Chat models of sizes 7B, 13B, and 70B and on the
Mixtral instruct model. Specifically, our fine-tuning technique significantly
reduces the rate at which the model refuses to follow harmful instructions. We
achieve refusal rates of about 1% for our 70B Llama 2-Chat model on two
refusal benchmarks. Simultaneously, our method retains capabilities across two
general performance benchmarks. We show that subversive fine-tuning is
practical and effective, and hence argue that evaluating risks from fine-tuning
should be a core part of risk assessments for releasing model weights. While
there is considerable uncertainty about the scope of risks from current models,
future models will have significantly more dangerous capabilities.

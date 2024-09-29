---
layout: publication
title: Lora Fine45;tuning Efficiently Undoes Safety Training In Llama 245;chat 70B
authors: Lermen Simon, Rogers-smith Charlie, Ladish Jeffrey
conference: "Arxiv"
year: 2023
bibkey: lermen2023lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.20624"}
tags: ['Agentic', 'Fine Tuning', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
AI developers often apply safety alignment procedures to prevent the misuse of their AI systems. For example before Meta released Llama 245;Chat 45; a collection of instruction fine45;tuned large language models 45; they invested heavily in safety training incorporating extensive red45;teaming and reinforcement learning from human feedback. We explore the robustness of safety training in language models by subversively fine45;tuning Llama 245;Chat. We employ quantized low45;rank adaptation (LoRA) as an efficient fine45;tuning method. With a budget of less than 200 and using only one GPU we successfully undo the safety training of Llama 245;Chat models of sizes 7B 13B and 70B and on the Mixtral instruct model. Specifically our fine45;tuning technique significantly reduces the rate at which the model refuses to follow harmful instructions. We achieve refusal rates of about 137; for our 70B Llama 245;Chat model on two refusal benchmarks. Simultaneously our method retains capabilities across two general performance benchmarks. We show that subversive fine45;tuning is practical and effective and hence argue that evaluating risks from fine45;tuning should be a core part of risk assessments for releasing model weights. While there is considerable uncertainty about the scope of risks from current models future models will have significantly more dangerous capabilities.

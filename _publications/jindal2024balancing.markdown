---
layout: publication
title: 'Balancing Continuous Pre-training And Instruction Fine-tuning: Optimizing Instruction-following In Llms'
authors: Ishan Jindal, Chandana Badrinath, Pranjal Bharti, Lakkidi Vinay, Sachin Dev Sharma
conference: "Arxiv"
year: 2024
bibkey: jindal2024balancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10739"}
tags: ['Pretraining Methods', 'Training Techniques', 'Pre-Training', 'Fine-Tuning']
---
Large Language Models (LLMs) for public use require continuous pre-training
to remain up-to-date with the latest data. The models also need to be
fine-tuned with specific instructions to maintain their ability to follow
instructions accurately. Typically, LLMs are released in two versions: the Base
LLM, pre-trained on diverse data, and the instruction-refined LLM, additionally
trained with specific instructions for better instruction following. The
question arises as to which model should undergo continuous pre-training to
maintain its instruction-following abilities while also staying current with
the latest data. In this study, we delve into the intricate relationship
between continuous pre-training and instruction fine-tuning of the LLMs and
investigate the impact of continuous pre-training on the instruction following
abilities of both the base and its instruction finetuned model. Further, the
instruction fine-tuning process is computationally intense and requires a
substantial number of hand-annotated examples for the model to learn
effectively. This study aims to find the most compute-efficient strategy to
gain up-to-date knowledge and instruction-following capabilities without
requiring any instruction data and fine-tuning. We empirically prove our
findings on the LLaMa 3, 3.1 and Qwen 2, 2.5 family of base and instruction
models, providing a comprehensive exploration of our hypotheses across varying
sizes of pre-training data corpus and different LLMs settings.

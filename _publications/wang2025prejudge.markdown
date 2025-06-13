---
layout: publication
title: 'Prejudge-before-think: Enhancing Large Language Models At Test-time By Process Prejudge Reasoning'
authors: Jianing Wang, Jin Jiang, Yang Liu, Mengdi Zhang, Xunliang Cai
conference: "Arxiv"
year: 2025
bibkey: wang2025prejudge
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.13500'}
  - {name: "Code", url: 'https://github.com/wjn1996/Prejudge-Before-Think'}
tags: ['Agentic', 'Has Code', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
In this paper, we introduce a new *process prejudge* strategy in LLM
reasoning to demonstrate that bootstrapping with process prejudge allows the
LLM to adaptively anticipate the errors encountered when advancing the
subsequent reasoning steps, similar to people sometimes pausing to think about
what mistakes may occur and how to avoid them, rather than relying solely on
trial and error. Specifically, we define a prejudge node in the rationale,
which represents a reasoning step, with at least one step that follows the
prejudge node that has no paths toward the correct answer. To synthesize the
prejudge reasoning process, we present an automated reasoning framework with a
dynamic tree-searching strategy. This framework requires only one LLM to
perform answer judging, response critiquing, prejudge generation, and thought
completion. Furthermore, we develop a two-phase training mechanism with
supervised fine-tuning (SFT) and reinforcement learning (RL) to further enhance
the reasoning capabilities of LLMs. Experimental results from competition-level
complex reasoning demonstrate that our method can teach the model to prejudge
before thinking and significantly enhance the reasoning ability of LLMs. Code
and data is released at https://github.com/wjn1996/Prejudge-Before-Think.

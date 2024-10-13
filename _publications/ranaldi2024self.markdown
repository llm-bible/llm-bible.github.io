---
layout: publication
title: 'Self-refine Instruction-tuning For Aligning Reasoning In Language Models'
authors: Ranaldi Leonardo, Freitas Andrè
conference: "Arxiv"
year: 2024
bibkey: ranaldi2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00402"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The alignments of reasoning abilities between smaller and larger Language
Models are largely conducted via Supervised Fine-Tuning (SFT) using
demonstrations generated from robust Large Language Models (LLMs). Although
these approaches deliver more performant models, they do not show sufficiently
strong generalization ability as the training only relies on the provided
demonstrations.
  In this paper, we propose the Self-refine Instruction-tuning method that
elicits Smaller Language Models to self-refine their abilities. Our approach is
based on a two-stage process, where reasoning abilities are first transferred
between LLMs and Small Language Models (SLMs) via Instruction-tuning on
demonstrations provided by LLMs, and then the instructed models Self-refine
their abilities through preference optimization strategies. In particular, the
second phase operates refinement heuristics based on the Direct Preference
Optimization algorithm, where the SLMs are elicited to deliver a series of
reasoning paths by automatically sampling the generated responses and providing
rewards using ground truths from the LLMs. Results obtained on commonsense and
math reasoning tasks show that this approach significantly outperforms
Instruction-tuning in both in-domain and out-domain scenarios, aligning the
reasoning abilities of Smaller and Larger Language Models.

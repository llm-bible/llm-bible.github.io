---
layout: publication
title: 'Rethinking Harmless Refusals When Fine-tuning Foundation Models'
authors: Florin Pop, Judd Rosenblatt, Diogo Schwerz De Lucena, Michael Vaiana
conference: "Arxiv"
year: 2024
bibkey: pop2024rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19552"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
In this paper, we investigate the degree to which fine-tuning in Large
Language Models (LLMs) effectively mitigates versus merely conceals undesirable
behavior. Through the lens of semi-realistic role-playing exercises designed to
elicit such behaviors, we explore the response dynamics of LLMs post
fine-tuning interventions. Our methodology involves prompting models for
Chain-of-Thought (CoT) reasoning and analyzing the coherence between the
reasoning traces and the resultant outputs. Notably, we identify a pervasive
phenomenon we term *reason-based deception*, where models either stop
producing reasoning traces or produce seemingly ethical reasoning traces that
belie the unethical nature of their final outputs. We further examine the
efficacy of response strategies (polite refusal versus explicit rebuttal) in
curbing the occurrence of undesired behavior in subsequent outputs of
multi-turn interactions. Our findings reveal that explicit rebuttals
significantly outperform polite refusals in preventing the continuation of
undesired outputs and nearly eliminate reason-based deception, challenging
current practices in model fine-tuning. Accordingly, the two key contributions
of this paper are (1) defining and studying reason-based deception, a new type
of hidden behavior, and (2) demonstrating that rebuttals provide a more robust
response model to harmful requests than refusals, thereby highlighting the need
to reconsider the response strategies in fine-tuning approaches.

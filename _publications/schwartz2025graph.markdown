---
layout: publication
title: 'Graph Of Attacks With Pruning: Optimizing Stealthy Jailbreak Prompt Generation For Enhanced LLM Content Moderation'
authors: Daniel Schwartz, Dmitriy Bespalov, Zhe Wang, Ninad Kulkarni, Yanjun Qi
conference: "Arxiv"
year: 2025
bibkey: schwartz2025graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.18638"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'GPT', 'Pruning', 'Model Architecture', 'Security', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
We present a modular pipeline that automates the generation of stealthy
jailbreak prompts derived from high-level content policies, enhancing LLM
content moderation. First, we address query inefficiency and jailbreak strength
by developing Graph of Attacks with Pruning (GAP), a method that utilizes
strategies from prior jailbreaks, resulting in 92% attack success rate on
GPT-3.5 using only 54% of the queries of the prior algorithm. Second, we
address the cold-start issue by automatically generating seed prompts from the
high-level policy using LLMs. Finally, we demonstrate the utility of these
generated jailbreak prompts of improving content moderation by fine-tuning
PromptGuard, a model trained to detect jailbreaks, increasing its accuracy on
the Toxic-Chat dataset from 5.1% to 93.89%.

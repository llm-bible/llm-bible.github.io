---
layout: publication
title: 'Pruning For Protection: Increasing Jailbreak Resistance In Aligned Llms Without Fine-tuning'
authors: Adib Hasan, Ileana Rugina, Alex Wang
conference: "Arxiv"
year: 2024
bibkey: hasan2024pruning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.10862"}
tags: ['Fine-Tuning', 'Responsible AI', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Security', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Quantization', 'Prompting']
---
This paper investigates the impact of model compression on the way Large
Language Models (LLMs) process prompts, particularly concerning jailbreak
resistance. We show that moderate WANDA pruning can enhance resistance to
jailbreaking attacks without fine-tuning, while maintaining performance on
standard benchmarks. To systematically evaluate this safety enhancement, we
introduce a dataset of 225 harmful tasks across five categories. Our analysis
of LLaMA-2 Chat, Vicuna 1.3, and Mistral Instruct v0.2 reveals that pruning
benefits correlate with initial model safety levels. We interpret these results
by examining changes in attention patterns and perplexity shifts, demonstrating
that pruned models exhibit sharper attention and increased sensitivity to
artificial jailbreak constructs. We extend our evaluation to the AdvBench
harmful behavior tasks and the GCG attack method. We find that LLaMA-2 is much
safer on AdvBench prompts than on our dataset when evaluated with manual
jailbreak attempts, and that pruning is effective against both automated
attacks and manual jailbreaking on Advbench.

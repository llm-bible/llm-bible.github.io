---
layout: publication
title: 'GASP: Efficient Black-box Generation Of Adversarial Suffixes For Jailbreaking Llms'
authors: Advik Raj Basani, Xiao Zhang
conference: "Arxiv"
year: 2024
bibkey: basani2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.14133'}
tags: ['RAG', 'Efficiency and Optimization', 'Security', 'Training Techniques', 'Tools', 'Prompting', 'Responsible AI']
---
Large Language Models (LLMs) have shown impressive proficiency across a range
of natural language processing tasks yet remain vulnerable to adversarial
prompts, known as jailbreak attacks, carefully designed to elicit harmful
responses from LLMs. Traditional methods rely on manual heuristics, which
suffer from limited generalizability. While being automatic, optimization-based
attacks often produce unnatural jailbreak prompts that are easy to detect by
safety filters or require high computational overhead due to discrete token
optimization. Witnessing the limitations of existing jailbreak methods, we
introduce Generative Adversarial Suffix Prompter (GASP), a novel framework that
combines human-readable prompt generation with Latent Bayesian Optimization
(LBO) to improve adversarial suffix creation in a fully black-box setting. GASP
leverages LBO to craft adversarial suffixes by efficiently exploring continuous
embedding spaces, gradually optimizing the model to improve attack efficacy
while balancing prompt coherence through a targeted iterative refinement
procedure. Our experiments show that GASP can generate natural jailbreak
prompts, significantly improving attack success rates, reducing training times,
and accelerating inference speed, thus making it an efficient and scalable
solution for red-teaming LLMs.

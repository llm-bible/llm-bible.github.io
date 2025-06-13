---
layout: publication
title: 'Rainbowplus: Enhancing Adversarial Prompt Generation Via Evolutionary Quality-diversity Search'
authors: Quy-anh Dang, Chris Ngo, Truong-son Hy
conference: "Arxiv"
year: 2025
bibkey: dang2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15047"}
  - {name: "Code", url: "https://github.com/knoveleng/rainbowplus,"}
tags: ['Responsible AI', 'Tools', 'Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Security', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) exhibit remarkable capabilities but are
susceptible to adversarial prompts that exploit vulnerabilities to produce
unsafe or biased outputs. Existing red-teaming methods often face scalability
challenges, resource-intensive requirements, or limited diversity in attack
strategies. We propose RainbowPlus, a novel red-teaming framework rooted in
evolutionary computation, enhancing adversarial prompt generation through an
adaptive quality-diversity (QD) search that extends classical evolutionary
algorithms like MAP-Elites with innovations tailored for language models. By
employing a multi-element archive to store diverse high-quality prompts and a
comprehensive fitness function to evaluate multiple prompts concurrently,
RainbowPlus overcomes the constraints of single-prompt archives and pairwise
comparisons in prior QD methods like Rainbow Teaming. Experiments comparing
RainbowPlus to QD methods across six benchmark datasets and four open-source
LLMs demonstrate superior attack success rate (ASR) and diversity
(Diverse-Score \\(\approx 0.84\\)), generating up to 100 times more unique prompts
(e.g., 10,418 vs. 100 for Ministral-8B-Instruct-2410). Against nine
state-of-the-art methods on the HarmBench dataset with twelve LLMs (ten
open-source, two closed-source), RainbowPlus achieves an average ASR of 81.1%,
surpassing AutoDAN-Turbo by 3.9%, and is 9 times faster (1.45 vs. 13.50 hours).
Our open-source implementation fosters further advancements in LLM safety,
offering a scalable tool for vulnerability assessment. Code and resources are
publicly available at https://github.com/knoveleng/rainbowplus, supporting
reproducibility and future research in LLM red-teaming.

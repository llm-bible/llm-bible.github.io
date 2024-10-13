---
layout: publication
title: 'Extend Model Merging From Fine-tuned To Pre-trained Large Language Models Via Weight Disentanglement'
authors: Yu Le, Yu Bowen, Yu Haiyang, Huang Fei, Li Yongbin
conference: "Arxiv"
year: 2024
bibkey: yu2024extend
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.03092"}
tags: ['Applications', 'Merging']
---
Merging Large Language Models (LLMs) aims to amalgamate multiple homologous
LLMs into one with all the capabilities. Ideally, any LLMs sharing the same
backbone should be mergeable, irrespective of whether they are Fine-Tuned (FT)
with minor parameter changes or Pre-Trained (PT) with substantial parameter
shifts. However, existing methods often manually assign the model importance,
rendering them feasible only for LLMs with similar parameter alterations, such
as multiple FT LLMs. The diverse parameter changed ranges between FT and PT
LLMs pose challenges for current solutions in empirically determining the
optimal combination. In this paper, we make a pioneering effort to broaden the
applicability of merging techniques from FT to PT LLMs. We initially examine
the efficacy of current methods in merging FT and PT LLMs, discovering that
they struggle to deal with PT LLMs. Subsequently, we introduce an approach
based on WeIght DisENtanglement (WIDEN) to effectively extend the merging
scope, which first disentangles model weights into magnitude and direction
components, and then performs adaptive fusion by considering their respective
contributions. In the experiments, we merge Qwen1.5-Chat (an FT LLM with
instruction-following skills) with Sailor (a PT LLM with multilingual
abilities) across 7B and 14B model scales. Results reveal that: (1) existing
solutions usually fail when merging Sailor, either losing both abilities or
only retaining instruction-following skills; (2) WIDEN successfully injects the
multilingual abilities of Sailor into Qwen1.5-Chat and make it proficient in
Southeast Asian languages, achieving enhancements in the fundamental
capabilities. In light of previous research, we also merge multiple 13B FT LLMs
and observe that WIDEN achieves a balanced amalgamation of instruction
following, mathematical reasoning, and code generation skills.

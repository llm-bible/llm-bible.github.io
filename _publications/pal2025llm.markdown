---
layout: publication
title: 'LLM Unlearning Reveals A Stronger-than-expected Coreset Effect In Current Benchmarks'
authors: Soumyadeep Pal, Changsheng Wang, James Diffenderfer, Bhavya Kailkhura, Sijia Liu
conference: "Arxiv"
year: 2025
bibkey: pal2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10185"}
  - {name: "Code", url: "https://github.com/OPTML-Group/MU-Coreset"}
tags: ['Responsible AI', 'Security', 'Efficiency and Optimization', 'Has Code']
---
Large language model unlearning has become a critical challenge in ensuring
safety and controlled model behavior by removing undesired data-model
influences from the pretrained model while preserving general utility.
Significant recent efforts have been dedicated to developing LLM unlearning
benchmarks such as WMDP (Weapons of Mass Destruction Proxy) and MUSE (Machine
Unlearning Six-way Evaluation), facilitating standardized unlearning
performance assessment and method comparison. Despite their usefulness, we
uncover for the first time a novel coreset effect within these benchmarks.
Specifically, we find that LLM unlearning achieved with the original (full)
forget set can be effectively maintained using a significantly smaller subset
(functioning as a "coreset"), e.g., as little as 5% of the forget set, even
when selected at random. This suggests that LLM unlearning in these benchmarks
can be performed surprisingly easily, even in an extremely low-data regime. We
demonstrate that this coreset effect remains strong, regardless of the LLM
unlearning method used, such as NPO (Negative Preference Optimization) and RMU
(Representation Misdirection Unlearning), the popular ones in these benchmarks.
The surprisingly strong coreset effect is also robust across various data
selection methods, ranging from random selection to more sophisticated
heuristic approaches. We explain the coreset effect in LLM unlearning through a
keyword-based perspective, showing that keywords extracted from the forget set
alone contribute significantly to unlearning effectiveness and indicating that
current unlearning is driven by a compact set of high-impact tokens rather than
the entire dataset. We further justify the faithfulness of coreset-unlearned
models along additional dimensions, such as mode connectivity and robustness to
jailbreaking attacks. Codes are available at
https://github.com/OPTML-Group/MU-Coreset.

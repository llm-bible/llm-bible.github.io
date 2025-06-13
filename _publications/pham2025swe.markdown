---
layout: publication
title: 'Swe-synth: Synthesizing Verifiable Bug-fix Data To Enable Large Language Models In Resolving Real-world Bugs'
authors: Minh V. T. Pham, Huy N. Phan, Hoang N. Phan, Cuong Le Chi, Tien N. Nguyen, Nghi D. Q. Bui
conference: "Arxiv"
year: 2025
bibkey: pham2025swe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.14757"}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG']
---
Large language models (LLMs) are transforming automated program repair (APR)
through agent-based approaches that localize bugs, generate patches, and verify
fixes. However, the lack of high-quality, scalable training datasets,
especially those with verifiable outputs and intermediate reasoning
traces-limits progress, particularly for open-source models. In this work, we
present SWE-Synth, a framework for synthesizing realistic, verifiable, and
process-aware bug-fix datasets at the repository level. SWE-Synth leverages LLM
agents to simulate debugging workflows, producing not only bug-fix pairs but
also test cases and structured repair trajectories. Compared to manually
curated datasets, our method scales with minimal human effort while preserving
contextual richness and correctness. Experiments show that models trained on
SWE-Synth outperform those trained on real-world datasets by 2.3% on SWE-Bench
Lite. Our results highlight the potential of synthetic, agent-generated data to
advance the state of the art in APR and software engineering automation.

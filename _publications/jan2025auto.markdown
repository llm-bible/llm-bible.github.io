---
layout: publication
title: 'Auto-patching: Enhancing Multi-hop Reasoning In Language Models'
authors: Aviv Jan, Dean Tahory, Omer Talmi, Omar Abo Mokh
conference: "Arxiv"
year: 2025
bibkey: jan2025auto
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00483'}
tags: ['Prompting', 'Tools']
---
Multi-hop questions still stump large language models (LLMs), which struggle to link information across multiple reasoning steps. We introduce Auto-Patch, a novel method that dynamically patches hidden states during inference to enhance multi-hop reasoning in LLMs. Building on the PatchScopes framework, Auto-Patch selectively modifies internal representations using a learned classifier. Evaluated on the MuSiQue dataset, Auto-Patch improves the solve rate from 18.45% (baseline) to 23.63~\\(\pm\\)~0.7% (3 runs), narrowing the gap to Chain-of-Thought prompting (27.44%). Our results highlight the potential of dynamic hidden state interventions for advancing complex reasoning in LLMs.

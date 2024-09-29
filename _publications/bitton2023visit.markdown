---
layout: publication
title: 'Visit-bench: A Benchmark For Vision-language Instruction Following Inspired By Real-world Use'
authors: Bitton Yonatan, Bansal Hritik, Hessel Jack, Shao Rulin, Zhu Wanrong, Awadalla Anas, Gardner Josh, Taori Rohan, Schmidt Ludwig
conference: "Arxiv"
year: 2023
bibkey: bitton2023visit
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.06595"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'TACL']
---
We introduce VisIT-Bench (Visual InsTruction Benchmark) a benchmark for evaluation of instruction-following vision-language models for real-world use. Our starting point is curating 70 instruction families that we envision instruction tuned vision-language models should be able to address. Extending beyond evaluations like VQAv2 and COCO tasks range from basic recognition to game playing and creative generation. Following curation our dataset comprises 592 test queries each with a human-authored instruction-conditioned caption. These descriptions surface instruction-specific factors e.g. for an instruction asking about the accessibility of a storefront for wheelchair users the instruction-conditioned caption describes ramps/potential obstacles. These descriptions enable 1) collecting human-verified reference outputs for each instance; and 2) automatic evaluation of candidate multimodal generations using a text-only LLM aligning with human judgment. We quantify quality gaps between models and references using both human and automatic evaluations; e.g. the top-performing instruction-following model wins against the GPT-4 reference in just 2737; of the comparison. VisIT-Bench is dynamic to participate practitioners simply submit their models response on the project website; Data code and leaderboard is available at visit-bench.github.io.

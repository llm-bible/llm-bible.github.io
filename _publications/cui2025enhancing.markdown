---
layout: publication
title: 'Enhancing Tool Learning In Large Language Models With Hierarchical Error Checklists'
authors: Yue Cui, Liuyi Yao, Shuchang Tao, Weijie Shi, Yaliang Li, Bolin Ding, Xiaofang Zhou
conference: "Arxiv"
year: 2025
bibkey: cui2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00042"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Applications']
---
Large language models (LLMs) have significantly advanced natural language processing, particularly through the integration of external tools and APIs. However, their effectiveness is frequently hampered by parameter mis-filling during tool calling. In this paper, we propose the Hierarchical Tool Error Checklist (HiTEC) framework to systematically diagnose and mitigate tool-calling errors without relying on extensive real-world interactions. HiTEC introduces a two-tiered approach: a global error checklist that identifies common, cross-tool issues, and a local error checklist that targets tool-specific and contextual failures. Building on this structure, we propose two deployments: HiTEC-In Context Learning (HiTEC-ICL) and HiTEC-Kahneman-Tversky Optimization (HiTEC-KTO). HiTEC-ICL embeds the global checklist in the initial prompts and leverages a two-round conversational interaction to dynamically refine parameter handling, while HiTEC-KTO generates high-quality negative examples to drive fine-tuning via preference-based optimization. Extensive experiments across five public datasets demonstrate that our framework significantly improves parameter-filling accuracy and tool-calling success rates compared to baseline methods.

---
layout: publication
title: Zero45;shot Visual Reasoning By Vision45;language Models Benchmarking And Analysis
authors: Nagar Aishik, Jaiswal Shantanu, Tan Cheston
conference: "Arxiv"
year: 2024
bibkey: nagar2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00106"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Vision45;language models (VLMs) have shown impressive zero45; and few45;shot performance on real45;world visual question answering (VQA) benchmarks alluding to their capabilities as visual reasoning engines. However the benchmarks being used conflate pure visual reasoning with world knowledge and also have questions that involve a limited number of reasoning steps. Thus it remains unclear whether a VLMs apparent visual reasoning performance is due to its world knowledge or due to actual visual reasoning capabilities. To clarify this ambiguity we systematically benchmark and dissect the zero45;shot visual reasoning capabilities of VLMs through synthetic datasets that require minimal world knowledge and allow for analysis over a broad range of reasoning steps. We focus on two novel aspects of zero45;shot visual reasoning i) evaluating the impact of conveying scene information as either visual embeddings or purely textual scene descriptions to the underlying large language model (LLM) of the VLM and ii) comparing the effectiveness of chain45;of45;thought prompting to standard prompting for zero45;shot visual reasoning. We find that the underlying LLMs when provided textual scene descriptions consistently perform better compared to being provided visual embeddings. In particular 1837; higher accuracy is achieved on the PTR dataset. We also find that CoT prompting performs marginally better than standard prompting only for the comparatively large GPT45;3.545;Turbo (175B) model and does worse for smaller45;scale models. This suggests the emergence of CoT abilities for visual reasoning in LLMs at larger scales even when world knowledge is limited. Overall we find limitations in the abilities of VLMs and LLMs for more complex visual reasoning and highlight the important role that LLMs can play in visual reasoning.

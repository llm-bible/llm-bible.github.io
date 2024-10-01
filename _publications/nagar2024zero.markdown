---
layout: publication
title: 'Zero-shot Visual Reasoning By Vision-language Models: Benchmarking And Analysis'
authors: Nagar Aishik, Jaiswal Shantanu, Tan Cheston
conference: "Arxiv"
year: 2024
bibkey: nagar2024zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00106"}
tags: ['Applications', 'Few Shot', 'GPT', 'Model Architecture', 'Multimodal Models', 'Prompting', 'Reinforcement Learning']
---
'Vision-language models (VLMs) have shown impressive zero- and few-shot performance on real-world visual question answering (VQA) benchmarks, alluding to their capabilities as visual reasoning engines. However, the benchmarks being used conflate pure visual reasoning with world knowledge, and also have questions that involve a limited number of reasoning steps. Thus, it remains unclear whether a VLM''s apparent visual reasoning performance is due to its world knowledge, or due to actual visual reasoning capabilities. To clarify this ambiguity, we systematically benchmark and dissect the zero-shot visual reasoning capabilities of VLMs through synthetic datasets that require minimal world knowledge, and allow for analysis over a broad range of reasoning steps. We focus on two novel aspects of zero-shot visual reasoning: i) evaluating the impact of conveying scene information as either visual embeddings or purely textual scene descriptions to the underlying large language model (LLM) of the VLM, and ii) comparing the effectiveness of chain-of-thought prompting to standard prompting for zero-shot visual reasoning. We find that the underlying LLMs, when provided textual scene descriptions, consistently perform better compared to being provided visual embeddings. In particular, 18&#37; higher accuracy is achieved on the PTR dataset. We also find that CoT prompting performs marginally better than standard prompting only for the comparatively large GPT-3.5-Turbo (175B) model, and does worse for smaller-scale models. This suggests the emergence of CoT abilities for visual reasoning in LLMs at larger scales even when world knowledge is limited. Overall, we find limitations in the abilities of VLMs and LLMs for more complex visual reasoning, and highlight the important role that LLMs can play in visual reasoning.'

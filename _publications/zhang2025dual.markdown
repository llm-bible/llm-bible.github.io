---
layout: publication
title: 'The Dual-use Dilemma In Llms: Do Empowering Ethical Capacities Make A Degraded Utility?'
authors: Yiyi Zhang, Xingyu Chen, Kexin Chen, Yuyang Du, Xilin Dang, Pheng-ann Heng
conference: "Arxiv"
year: 2025
bibkey: zhang2025dual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.13952"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Ethics and Bias', 'Applications', 'Attention Mechanism']
---
Recent years have witnessed extensive efforts to enhance Large Language
Models (LLMs) across various domains, alongside growing attention to their
ethical implications. However, a critical challenge remains largely overlooked:
LLMs must balance between rejecting harmful requests for safety and
accommodating legitimate ones for utility. This paper presents a Direct
Preference Optimization (DPO) based alignment framework that achieves better
overall performance by addressing this ethical-utility trade-off, using
chemical domain applications as a proof-of-concept. Our alignment pipeline
starts with a GPT-assisted three-phase data generation scheme, in which we
create LibraChemQA, a chemical question-answering dataset comprising 31.6k
triplet instances. By incorporating an innovative balanced seed in the data
generation process, our framework systematically considers both legitimate and
illegitimate requests. The framework also introduces a rephrasing mechanism for
efficient data augmentation that enhances the model's chemical comprehension.
We further develop a novel hybrid evaluation scheme with LLM judges for precise
assessment of both safety and utility. Experimental results demonstrate our
model's substantial improvements in overall performance where both safety and
utility are considered - the resulting model outperforms leading LLMs including
Claude-3, GPT-4o, and LLaMA-3 by margins of 13.44%, 7.16%, and 7.10%
respectively on our released benchmark. At the end of this paper, we analyze
experimental results obtained from testing DeepSeek-R1 on our benchmark and
reveal the critical ethical concerns raised by this highly acclaimed model. We
highlight that the long Chain-of-Thought (CoT) reasoning process employed by
DeepSeek-R1, as well as other LLMs distilled from it, introduces significant
ethical vulnerabilities when exposed to users.

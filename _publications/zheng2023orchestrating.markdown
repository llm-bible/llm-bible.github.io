---
layout: publication
title: Lyra&#58; Orchestrating Dual Correction In Automated Theorem Proving
authors: Zheng Chuanyang, Wang Haiming, Xie Enze, Liu Zhengying, Sun Jiankai, Xin Huajian, Shen Jianhao, Li Zhenguo, Li Yu
conference: "Arxiv"
year: 2023
bibkey: zheng2023orchestrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.15806"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) present an intriguing avenue for exploration in the field of formal theorem proving. Nevertheless their full potential particularly concerning the mitigation of hallucinations and refinement through prover error messages remains an area that has yet to be thoroughly investigated. To enhance the effectiveness of LLMs in the field we introduce the Lyra a new framework that employs two distinct correction mechanisms Tool Correction (TC) and Conjecture Correction (CC). To implement Tool Correction in the post-processing of formal proofs we leverage prior knowledge to utilize predefined prover tools (e.g. Sledgehammer) for guiding the replacement of incorrect tools. Tool Correction significantly contributes to mitigating hallucinations thereby improving the overall accuracy of the proof. In addition we introduce Conjecture Correction an error feedback mechanism designed to interact with prover to refine formal proof conjectures with prover error messages. Compared to the previous refinement framework the proposed Conjecture Correction refines generation with instruction but does not collect paired (generation error amp; refinement) prompts. Our method has achieved state-of-the-art (SOTA) performance on both miniF2F validation (48.037; - 55.337;) and test (45.537; - 51.237;). We also present 3 IMO problems solved by Lyra. We believe Tool Correction (post-process for hallucination mitigation) and Conjecture Correction (subgoal adjustment from interaction with environment) could provide a promising avenue for future research in this field.

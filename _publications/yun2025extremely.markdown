---
layout: publication
title: 'Ultragen: Extremely Fine-grained Controllable Generation Via Attribute Reconstruction And Global Preference Optimization'
authors: Longfei Yun, Letian Peng, Jingbo Shang
conference: "Arxiv"
year: 2025
bibkey: yun2025extremely
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12375"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Language Modeling', 'Ethics and Bias', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Fine granularity is an essential requirement for controllable text
generation, which has seen rapid growth with the ability of LLMs. However,
existing methods focus mainly on a small set of attributes like 3 to 5, and
their performance degrades significantly when the number of attributes
increases to the next order of magnitude. To address this challenge, we propose
a novel zero-shot approach for extremely fine-grained controllable generation
(EFCG), proposing auto-reconstruction (AR) and global preference optimization
(GPO). In the AR phase, we leverage LLMs to extract soft attributes (e.g.,
Emphasis on simplicity and minimalism in design) from raw texts, and combine
them with programmatically derived hard attributes (e.g., The text should be
between 300 and 400 words) to construct massive (around 45) multi-attribute
requirements, which guide the fine-grained text reconstruction process under
weak supervision. In the GPO phase, we apply direct preference optimization
(DPO) to refine text generation under diverse attribute combinations, enabling
efficient exploration of the global combination space. Additionally, we
introduce an efficient attribute sampling strategy to identify and correct
potentially erroneous attributes, further improving global optimization. Our
framework significantly improves the constraint satisfaction rate (CSR) and
text quality for EFCG by mitigating position bias and alleviating attention
dilution.

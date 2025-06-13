---
layout: publication
title: 'Property Enhanced Instruction Tuning For Multi-task Molecule Generation With Large Language Models'
authors: Xuan Lin, Long Chen, Yile Wang, Xiangxiang Zeng, Philip S. Yu
conference: "Arxiv"
year: 2024
bibkey: lin2024property
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18084"}
  - {name: "Code", url: "https://github.com/chenlong164/PEIT"}
tags: ['Tools', 'Multimodal Models', 'Has Code', 'Applications']
---
Large language models (LLMs) are widely applied in various natural language processing tasks such as question answering and machine translation. However, due to the lack of labeled data and the difficulty of manual annotation for biochemical properties, the performance for molecule generation tasks is still limited, especially for tasks involving multi-properties constraints. In this work, we present a two-step framework PEIT (Property Enhanced Instruction Tuning) to improve LLMs for molecular-related tasks. In the first step, we use textual descriptions, SMILES, and biochemical properties as multimodal inputs to pre-train a model called PEIT-GEN, by aligning multi-modal representations to synthesize instruction data. In the second step, we fine-tune existing open-source LLMs with the synthesized data, the resulting PEIT-LLM can handle molecule captioning, text-based molecule generation, molecular property prediction, and our newly proposed multi-constraint molecule generation tasks. Experimental results show that our pre-trained PEIT-GEN outperforms MolT5 and BioT5 in molecule captioning, demonstrating modalities align well between textual descriptions, structures, and biochemical properties. Furthermore, PEIT-LLM shows promising improvements in multi-task molecule generation, proving the scalability of the PEIT framework for various molecular tasks. We release the code, constructed instruction data, and model checkpoints in https://github.com/chenlong164/PEIT.

---
layout: publication
title: 'Prottex: Structure-in-context Reasoning And Editing Of Proteins With Large Language Models'
authors: Zicheng Ma, Chuanliu Fan, Zhicong Wang, Zhenyu Chen, Xiaohan Lin, Yanheng Li, Shihao Feng, Jun Zhang, Ziqiang Cao, Yi Qin Gao
conference: "Arxiv"
year: 2025
bibkey: ma2025structure
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08179"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Tokenization', 'Multimodal Models']
---
Large language models have made remarkable progress in the field of molecular
science, particularly in understanding and generating functional small
molecules. This success is largely attributed to the effectiveness of molecular
tokenization strategies. In protein science, the amino acid sequence serves as
the sole tokenizer for LLMs. However, many fundamental challenges in protein
science are inherently structure-dependent. The absence of structure-aware
tokens significantly limits the capabilities of LLMs for comprehensive
biomolecular comprehension and multimodal generation. To address these
challenges, we introduce a novel framework, ProtTeX, which tokenizes the
protein sequences, structures, and textual information into a unified discrete
space. This innovative approach enables joint training of the LLM exclusively
through the Next-Token Prediction paradigm, facilitating multimodal protein
reasoning and generation. ProtTeX enables general LLMs to perceive and process
protein structures through sequential text input, leverage structural
information as intermediate reasoning components, and generate or manipulate
structures via sequential text output. Experiments demonstrate that our model
achieves significant improvements in protein function prediction, outperforming
the state-of-the-art domain expert model with a twofold increase in accuracy.
Our framework enables high-quality conformational generation and customizable
protein design. For the first time, we demonstrate that by adopting the
standard training and inference pipelines from the LLM domain, ProtTeX empowers
decoder-only LLMs to effectively address diverse spectrum of protein-related
tasks.

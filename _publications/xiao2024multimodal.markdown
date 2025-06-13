---
layout: publication
title: 'Proteingpt: Multimodal LLM For Protein Property Prediction And Structure Understanding'
authors: Yijia Xiao, Edward Sun, Yiqiao Jin, Qifan Wang, Wei Wang
conference: "Arxiv"
year: 2024
bibkey: xiao2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11363"}
  - {name: "Code", url: "https://github.com/ProteinGPT/ProteinGPT"}
tags: ['Fine-Tuning', 'GPT', 'RAG', 'Model Architecture', 'Has Code', 'Multimodal Models']
---
Understanding biological processes, drug development, and biotechnological
advancements requires a detailed analysis of protein structures and functions,
a task that is inherently complex and time-consuming in traditional protein
research. To streamline this process, we introduce ProteinGPT, a
state-of-the-art multimodal large language model for proteins that enables
users to upload protein sequences and/or structures for comprehensive analysis
and responsive inquiries. ProteinGPT integrates protein sequence and structure
encoders with linear projection layers to ensure precise representation
adaptation and leverages a large language model (LLM) to generate accurate,
contextually relevant responses. To train ProteinGPT, we constructed a
large-scale dataset of 132,092 proteins, each annotated with 20-30 property
tags and 5-10 QA pairs per protein, and optimized the instruction-tuning
process using GPT-4o. Experiments demonstrate that ProteinGPT effectively
generates informative responses to protein-related questions, achieving high
performance on both semantic and lexical metrics and significantly
outperforming baseline models and general-purpose LLMs in understanding and
responding to protein-related queries. Our code and data are available at
https://github.com/ProteinGPT/ProteinGPT.

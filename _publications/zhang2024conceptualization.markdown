---
layout: publication
title: 'Conke: Conceptualization-augmented Knowledge Editing In Large Language Models For Commonsense Reasoning'
authors: Liyu Zhang, Weiqi Wang, Tianqing Fang, Yangqiu Song
conference: "Arxiv"
year: 2024
bibkey: zhang2024conceptualization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.11418"}
  - {name: "Code", url: "https://github.com/HKUST-KnowComp/ConKE"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Has Code', 'Applications']
---
Knowledge Editing (KE) aims to adjust a Large Language Model's (LLM) internal representations and parameters to correct inaccuracies and improve output consistency without incurring the computational expense of re-training the entire model. However, editing commonsense knowledge still faces difficulties, including limited knowledge coverage in existing resources, the infeasibility of annotating labels for an overabundance of commonsense knowledge, and the strict knowledge formats of current editing methods. In this paper, we address these challenges by presenting ConceptEdit, a framework that integrates conceptualization and instantiation into the KE pipeline for LLMs to enhance their commonsense reasoning capabilities. ConceptEdit dynamically diagnoses implausible commonsense knowledge within an LLM using another verifier LLM and augments the source knowledge to be edited with conceptualization for stronger generalizability. Experimental results demonstrate that LLMs enhanced with ConceptEdit successfully generate commonsense knowledge with improved plausibility compared to other baselines and achieve stronger performance across multiple question answering benchmarks. Our data, code, and models are publicly available at https://github.com/HKUST-KnowComp/ConKE.

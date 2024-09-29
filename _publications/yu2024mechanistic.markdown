---
layout: publication
title: Mechanistic Understanding and Mitigation of Language Model Non-Factual Hallucinations
authors: Yu Lei, Cao Meng, Cheung Jackie Chi Kit, Dong Yue
conference: "Arxiv"
year: 2024
bibkey: yu2024mechanistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18167"}
tags: ['Attention Mechanism', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Reinforcement Learning']
---
State-of-the-art language models (LMs) sometimes generate non-factual hallucinations that misalign with world knowledge. To explore the mechanistic causes of these hallucinations we create diagnostic datasets with subject-relation queries and adapt interpretability methods to trace hallucinations through internal model representations. We discover two general and distinct mechanistic causes of hallucinations shared across LMs (Llama-2 Pythia GPT-J) 1) knowledge enrichment hallucinations insufficient subject attribute knowledge in lower layer MLPs and 2) answer extraction hallucinations failure to select the correct object attribute in upper layer attention heads. We also found these two internal mechanistic causes of hallucinations are reflected in external manifestations. Based on insights from our mechanistic analysis we propose a novel hallucination mitigation method through targeted restoration of the LMs internal fact recall pipeline demonstrating superior performance compared to baselines.

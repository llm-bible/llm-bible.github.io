---
layout: publication
title: 'NILE: Internal Consistency Alignment In Large Language Models'
authors: Minda Hu, Qiyuan Zhang, Yufei Wang, Bowei He, Hongru Wang, Jingyan Zhou, Liangyou Li, Yasheng Wang, Chen Ma, Irwin King
conference: "Arxiv"
year: 2024
bibkey: hu2024internal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.16686"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
As a crucial step to enhance LLMs alignment with human intentions,
Instruction Fine-Tuning (IFT) has a high demand on dataset quality. However,
existing IFT datasets often contain knowledge that is inconsistent with LLMs'
internal knowledge learned from the pre-training phase, which can greatly
affect the efficacy of IFT. To address this issue, we introduce NILE (iNternal
consIstency aLignmEnt) framework, aimed at optimizing IFT datasets to unlock
LLMs' capability further. NILE operates by eliciting target pre-trained LLM's
internal knowledge corresponding to instruction data. The internal knowledge is
leveraged to revise the answer in IFT datasets. Additionally, we propose a
novel Internal Consistency Filtering (ICF) method to filter training samples,
ensuring its high consistency with LLM's internal knowledge. Our experiments
demonstrate that NILE-aligned IFT datasets sharply boost LLM performance across
multiple LLM ability evaluation datasets, achieving up to 66.6% gain on
Arena-Hard and 68.5% on Alpaca-Eval V2. Further analysis confirms that each
component of the NILE\}framework contributes to these substantial performance
improvements, and provides compelling evidence that dataset consistency with
pre-trained internal knowledge is pivotal for maximizing LLM potential.

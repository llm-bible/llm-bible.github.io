---
layout: publication
title: 'Towards Comprehensive And Efficient Post Safety Alignment Of Large Language Models Via Safety Patching'
authors: Zhao Weixiang, Hu Yulin, Li Zhuojun, Deng Yang, Zhao Yanyan, Qin Bing, Chua Tat-seng
conference: "Arxiv"
year: 2024
bibkey: zhao2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13820"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Responsible AI', 'Tools']
---
Safety alignment of large language models (LLMs) has been gaining increasing attention. However current safety-aligned LLMs suffer from the fragile and imbalanced safety mechanisms which can still be induced to generate unsafe responses exhibit over-safety by rejecting safe user inputs and fail to preserve general utility after safety alignment. To this end we propose a novel post safety alignment (PSA) method to address these inherent and emerging safety challenges including safety enhancement over-safety mitigation and utility preservation. In specific we introduce (textscSafePatching) a novel framework for comprehensive and efficient PSA where two distinct safety patches are developed on the harmful data to enhance safety and mitigate over-safety concerns and then seamlessly integrated into the target LLM backbone without compromising its utility. Extensive experiments show that (textscSafePatching) achieves a more comprehensive and efficient PSA than baseline methods. It even enhances the utility of the backbone further optimizing the balance between being helpful and harmless in current aligned LLMs. Also (textscSafePatching) demonstrates its superiority in continual PSA scenarios.

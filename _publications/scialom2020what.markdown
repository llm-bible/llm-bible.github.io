---
layout: publication
title: What BERT Sees&#58; Cross-modal Transfer For Visual Question Generation
authors: Scialom Thomas, Bordes Patrick, Dray Paul-alexis, Staiano Jacopo, Gallinari Patrick
conference: "Arxiv"
year: 2020
bibkey: scialom2020what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.10832"}
tags: ['Applications', 'BERT', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'RAG', 'Training Techniques']
---
Pre-trained language models have recently contributed to significant advances in NLP tasks. Recently multi-modal versions of BERT have been developed using heavy pre-training relying on vast corpora of aligned textual and image data primarily applied to classification tasks such as VQA. In this paper we are interested in evaluating the visual capabilities of BERT out-of-the-box by avoiding pre-training made on supplementary data. We choose to study Visual Question Generation a task of great interest for grounded dialog that enables to study the impact of each modality (as input can be visual and/or textual). Moreover the generation aspect of the task requires an adaptation since BERT is primarily designed as an encoder. We introduce BERT-gen a BERT-based architecture for text generation able to leverage on either mono- or multi- modal representations. The results reported under different configurations indicate an innate capacity for BERT-gen to adapt to multi-modal data and text generation even with few data available avoiding expensive pre-training. The proposed model obtains substantial improvements over the state-of-the-art on two established VQG datasets.

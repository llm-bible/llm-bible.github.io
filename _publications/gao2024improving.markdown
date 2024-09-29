---
layout: publication
title: 'Improving Language Understanding From Screenshots'
authors: Gao Tianyu, Wang Zirui, Bhaskar Adithya, Chen Danqi
conference: "Arxiv"
year: 2024
bibkey: gao2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14073"}
tags: ['Applications', 'BERT', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
An emerging family of language models (LMs) capable of processing both text and images within a single visual view has the promise to unlock complex tasks such as chart understanding and UI navigation. We refer to these models as screenshot language models. Despite their appeal existing screenshot LMs substantially lag behind text-only models on language understanding tasks. To close this gap we adopt a simplified setting where the model inputs are plain-text-rendered screenshots and we focus on improving the text ability of screenshot LMs. We propose a novel Patch-and-Text Prediction (PTP) objective which masks and recovers both image patches of screenshots and text within screenshots. We also conduct extensive ablation studies on masking rates and patch sizes as well as designs for improving training stability. Our pre-trained model while solely taking visual inputs achieves comparable performance with BERT on 6 out of 8 GLUE tasks (within 237;) and improves up to 837; over prior work. Additionally we extend PTP to train autoregressive screenshot LMs and demonstrate its effectiveness--our models can significantly reduce perplexity by utilizing the screenshot context. Together we hope our findings can inspire future research on developing powerful screenshot LMs and extending their reach to broader applications.

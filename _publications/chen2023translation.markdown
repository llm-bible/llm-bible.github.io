---
layout: publication
title: 'Translation And Fusion Improves Zero-shot Cross-lingual Information Extraction'
authors: Chen Yang, Shah Vedaant, Ritter Alan
conference: "Arxiv"
year: 2023
bibkey: chen2023translation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13582"}
tags: ['Fine Tuning', 'GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Large language models (LLMs) combined with instruction tuning have shown significant progress in information extraction (IE) tasks, exhibiting strong generalization capabilities to unseen datasets by following annotation guidelines. However, their applicability to low-resource languages remains limited due to lack of both labeled data for fine-tuning, and unlabeled text for pre-training. In this paper, we propose TransFusion, a framework in which models are fine-tuned to use English translations of low-resource language data, enabling more precise predictions through annotation fusion. Based on TransFusion, we introduce GoLLIE-TF, a cross-lingual instruction-tuned LLM for IE tasks, designed to close the performance gap between high and low-resource languages. Our experiments across twelve multilingual IE datasets spanning 50 languages demonstrate that GoLLIE-TF achieves better zero-shot cross-lingual transfer over the base model. In addition, we show that TransFusion significantly improves low-resource language named entity recognition when applied to proprietary models such as GPT-4 (+5 F1) with a prompting approach, or fine-tuning different language models including decoder-only (+14 F1) and encoder-only (+13 F1) architectures.

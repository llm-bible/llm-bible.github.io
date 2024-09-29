---
layout: publication
title: Translation And Fusion Improves Zero45;shot Cross45;lingual Information Extraction
authors: Chen Yang, Shah Vedaant, Ritter Alan
conference: "Arxiv"
year: 2023
bibkey: chen2023translation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13582"}
tags: ['GPT', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Large language models (LLMs) combined with instruction tuning have shown significant progress in information extraction (IE) tasks exhibiting strong generalization capabilities to unseen datasets by following annotation guidelines. However their applicability to low45;resource languages remains limited due to lack of both labeled data for fine45;tuning and unlabeled text for pre45;training. In this paper we propose TransFusion a framework in which models are fine45;tuned to use English translations of low45;resource language data enabling more precise predictions through annotation fusion. Based on TransFusion we introduce GoLLIE45;TF a cross45;lingual instruction45;tuned LLM for IE tasks designed to close the performance gap between high and low45;resource languages. Our experiments across twelve multilingual IE datasets spanning 50 languages demonstrate that GoLLIE45;TF achieves better zero45;shot cross45;lingual transfer over the base model. In addition we show that TransFusion significantly improves low45;resource language named entity recognition when applied to proprietary models such as GPT45;4 (+5 F1) with a prompting approach or fine45;tuning different language models including decoder45;only (+14 F1) and encoder45;only (+13 F1) architectures.

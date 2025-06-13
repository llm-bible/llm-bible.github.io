---
layout: publication
title: 'Analyzing Mitigation Strategies For Catastrophic Forgetting In End-to-end Training Of Spoken Language Models'
authors: Chi-yuan Hsiao, Ke-han Lu, Kai-wei Chang, Chih-kai Yang, Wei-chih Chen, Hung-yi Lee
conference: "Arxiv"
year: 2025
bibkey: hsiao2025analyzing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17496"}
tags: ['Fine-Tuning', 'Training Techniques', 'Applications', 'Merging']
---
End-to-end training of Spoken Language Models (SLMs) commonly involves adapting pre-trained text-based Large Language Models (LLMs) to the speech modality through multi-stage training on diverse tasks such as ASR, TTS and spoken question answering (SQA). Although this multi-stage continual learning equips LLMs with both speech understanding and generation capabilities, the substantial differences in task and data distributions across stages can lead to catastrophic forgetting, where previously acquired knowledge is lost. This paper investigates catastrophic forgetting and evaluates three mitigation strategies-model merging, discounting the LoRA scaling factor, and experience replay to balance knowledge retention with new learning. Results show that experience replay is the most effective, with further gains achieved by combining it with other methods. These findings provide insights for developing more robust and efficient SLM training pipelines.

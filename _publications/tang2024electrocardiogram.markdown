---
layout: publication
title: 'Electrocardiogram-language Model For Few-shot Question Answering With Meta Learning'
authors: Jialu Tang, Tong Xia, Yuan Lu, Cecilia Mascolo, Aaqib Saeed
conference: "Arxiv"
year: 2024
bibkey: tang2024electrocardiogram
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14464"}
tags: ['Applications', 'RAG', 'Merging', 'Reinforcement Learning', 'Few-Shot', 'Multimodal Models']
---
Electrocardiogram (ECG) interpretation requires specialized expertise, often
involving synthesizing insights from ECG signals with complex clinical queries
posed in natural language. The scarcity of labeled ECG data coupled with the
diverse nature of clinical inquiries presents a significant challenge for
developing robust and adaptable ECG diagnostic systems. This work introduces a
novel multimodal meta-learning method for few-shot ECG question answering,
addressing the challenge of limited labeled data while leveraging the rich
knowledge encoded within large language models (LLMs). Our LLM-agnostic
approach integrates a pre-trained ECG encoder with a frozen LLM (e.g., LLaMA
and Gemma) via a trainable fusion module, enabling the language model to reason
about ECG data and generate clinically meaningful answers. Extensive
experiments demonstrate superior generalization to unseen diagnostic tasks
compared to supervised baselines, achieving notable performance even with
limited ECG leads. For instance, in a 5-way 5-shot setting, our method using
LLaMA-3.1-8B achieves an accuracy of 84.6%, 77.3%, and 69.6% on single verify,
choose and query question types, respectively. These results highlight the
potential of our method to enhance clinical ECG interpretation by combining
signal processing with the nuanced language understanding capabilities of LLMs,
particularly in data-constrained scenarios.

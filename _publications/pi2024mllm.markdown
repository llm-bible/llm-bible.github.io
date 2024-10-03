---
layout: publication
title: 'Mllm-protector: Ensuring Mllm''s Safety Without Hurting Performance'
authors: Pi Renjie, Han Tianyang, Zhang Jianshu, Xie Yueqi, Pan Rui, Lian Qing, Dong Hanze, Zhang Jipeng, Zhang Tong
conference: "Arxiv"
year: 2024
bibkey: pi2024mllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.02906"}
tags: ['Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Responsible AI', 'Security', 'Training Techniques']
---
The deployment of multimodal large language models (MLLMs) has brought forth a unique vulnerability: susceptibility to malicious attacks through visual inputs. This paper investigates the novel challenge of defending MLLMs against such attacks. Compared to large language models (LLMs), MLLMs include an additional image modality. We discover that images act as a foreign language that is not considered during safety alignment, making MLLMs more prone to producing harmful responses. Unfortunately, unlike the discrete tokens considered in text-based LLMs, the continuous nature of image signals presents significant alignment challenges, which poses difficulty to thoroughly cover all possible scenarios. This vulnerability is exacerbated by the fact that most state-of-the-art MLLMs are fine-tuned on limited image-text pairs that are much fewer than the extensive text-based pretraining corpus, which makes the MLLMs more prone to catastrophic forgetting of their original abilities during safety fine-tuning. To tackle these challenges, we introduce MLLM-Protector, a plug-and-play strategy that solves two subtasks: 1) identifying harmful responses via a lightweight harm detector, and 2) transforming harmful responses into harmless ones via a detoxifier. This approach effectively mitigates the risks posed by malicious visual inputs without compromising the original performance of MLLMs. Our results demonstrate that MLLM-Protector offers a robust solution to a previously unaddressed aspect of MLLM security.

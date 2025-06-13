---
layout: publication
title: 'Controlling Language Confusion In Multilingual Llms'
authors: Nahyun Lee, Yeongseo Woo, Hyunwoo Ko, Guijin Son
conference: "Arxiv"
year: 2025
bibkey: lee2025controlling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19116'}
tags: ['Merging', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Large language models often suffer from language confusion, a phenomenon where responses are partially or entirely generated in unintended languages. This can critically impact user experience in low-resource settings. We hypothesize that conventional supervised fine-tuning exacerbates this issue because the softmax objective focuses probability mass only on the single correct token but does not explicitly penalize cross-lingual mixing. Interestingly, by observing loss trajectories during the pretraining phase, we observe that models fail to learn to distinguish between monolingual and language-confused text. Additionally, we find that ORPO, which adds penalties for unwanted output styles to standard SFT, effectively suppresses language-confused generations even at high decoding temperatures without degrading overall model performance. Our findings suggest that incorporating appropriate penalty terms can mitigate language confusion in low-resource settings with limited data.

---
layout: publication
title: Calibrating Long-form Generations From Large Language Models
authors: Huang Yukun, Liu Yixin, Thirukovalluru Raghuveer, Cohan Arman, Dhingra Bhuwan
conference: "Arxiv"
year: 2024
bibkey: huang2024calibrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.06544"}
tags: ['Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
To enhance Large Language Models (LLMs) reliability calibration is essential -- the models assessed confidence scores should align with the actual likelihood of its responses being correct. However current confidence elicitation methods and calibration metrics typically rely on a binary true/false assessment of response correctness. This approach does not apply to long-form generation where an answer can be partially correct. Addressing this gap we introduce a unified calibration framework in which both the correctness of the LLMs responses and their associated confidence levels are treated as distributions across a range of scores. Within this framework we develop three metrics to precisely evaluate LLM calibration and further propose two confidence elicitation methods based on self-consistency and self-evaluation. Our experiments which include long-form QA and summarization tasks demonstrate that larger models dont necessarily guarantee better calibration that calibration performance is found to be metric-dependent and that self-consistency methods excel in factoid datasets. We also find that calibration can be enhanced through techniques such as fine-tuning integrating relevant source documents scaling the temperature and combining self-consistency with self-evaluation. Lastly we showcase a practical application of our system selecting and cascading open-source models and ChatGPT to optimize correctness given a limited API budget. This research not only challenges existing notions of LLM calibration but also offers practical methodologies for improving trustworthiness in long-form generation.

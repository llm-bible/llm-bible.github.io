---
layout: publication
title: 'Reinforcement Learning Vs. Distillation: Understanding Accuracy And Capability In LLM Reasoning'
authors: Minwu Kim, Anubhav Shrestha, Safal Shrestha, Aadim Nepal, Keith Ross
conference: "Arxiv"
year: 2025
bibkey: kim2025reinforcement
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.14216'}
tags: ['Agentic', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Reinforcement Learning']
---
Recent studies have shown that reinforcement learning with verifiable rewards (RLVR) enhances overall accuracy but fails to improve capability, while distillation can improve both. In this paper, we investigate the mechanisms behind these phenomena. First, we demonstrate that RLVR does not improve capability because it focuses on improving the accuracy of the less-difficult questions to the detriment of the accuracy of the most difficult questions, thereby leading to no improvement in capability. Second, we find that RLVR does not merely increase the success probability for the less difficult questions, but in our small model settings produces quality responses that were absent in its output distribution before training. In addition, we show these responses are neither noticeably longer nor feature more reflection-related keywords, underscoring the need for more reliable indicators of response quality. Third, we show that while distillation reliably improves accuracy by learning strong reasoning patterns, it only improves capability when new knowledge is introduced. Moreover, when distilling only with reasoning patterns and no new knowledge, the accuracy of the less-difficult questions improves to the detriment of the most difficult questions, similar to RLVR. Together, these findings offer a clearer understanding of how RLVR and distillation shape reasoning behavior in language models.

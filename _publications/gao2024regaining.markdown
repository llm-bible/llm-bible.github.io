---
layout: publication
title: 'Coca: Regaining Safety-awareness Of Multimodal Large Language Models With Constitutional Calibration'
authors: Jiahui Gao, Renjie Pi, Tianyang Han, Han Wu, Lanqing Hong, Lingpeng Kong, Xin Jiang, Zhenguo Li
conference: "Arxiv"
year: 2024
bibkey: gao2024regaining
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.11365'}
tags: ['Multimodal Models', 'Responsible AI', 'Security']
---
The deployment of multimodal large language models (MLLMs) has demonstrated
remarkable success in engaging in conversations involving visual inputs, thanks
to the superior power of large language models (LLMs). Those MLLMs are
typically built based on the LLMs, with an image encoder to process images into
the token embedding space of the LLMs. However, the integration of visual
modality has introduced a unique vulnerability: the MLLM becomes susceptible to
malicious visual inputs and prone to generating sensitive or harmful responses,
even though the LLM has been trained on textual dataset to align with human
value. In this paper, we first raise the question: ``Do the MLLMs possess
safety-awareness against malicious image inputs?". We find that after adding a
principle that specifies the safety requirement into the input of the MLLM, the
model's safety awareness becomes boosted. This phenomenon verifies the
existence of MLLM's safety-awareness against image inputs, it is only weakened
by the modality gap. We then introduce a simple yet effective technique termed
CoCA, which amplifies the safety-awareness of the MLLM by calibrating its
output distribution. Our proposed strategy helps the model reclaim its original
safety awareness without losing its original capabilities. We verify the
effectiveness of our approach on both multimodal safety and understanding
benchmarks.

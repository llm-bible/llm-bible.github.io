---
layout: publication
title: 'Adversarial DPO: Harnessing Harmful Data For Reducing Toxicity With Minimal Impact On Coherence And Evasiveness In Dialogue Agents'
authors: San Kim, Gary Geunbae Lee
conference: "Arxiv"
year: 2024
bibkey: kim2024adversarial
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12900"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning', 'Applications']
---
Recent advancements in open-domain dialogue systems have been propelled by
the emergence of high-quality large language models (LLMs) and various
effective training methodologies. Nevertheless, the presence of toxicity within
these models presents a significant challenge that can potentially diminish the
user experience. In this study, we introduce an innovative training algorithm,
an improvement upon direct preference optimization (DPO), called adversarial
DPO (ADPO). The ADPO algorithm is designed to train models to assign higher
probability distributions to preferred responses and lower distributions to
unsafe responses, which are self-generated using the toxic control token. We
demonstrate that ADPO enhances the model's resilience against harmful
conversations while minimizing performance degradation. Furthermore, we
illustrate that ADPO offers a more stable training procedure compared to the
traditional DPO. To the best of our knowledge, this is the first adaptation of
the DPO algorithm that directly incorporates harmful data into the generative
model, thereby reducing the need to artificially create safe dialogue data.

---
layout: publication
title: 'The Energy Cost Of Reasoning: Analyzing Energy Usage In Llms With Test-time Compute'
authors: Yunho Jin, Gu-yeon Wei, David Brooks
conference: "Arxiv"
year: 2025
bibkey: jin2025energy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14733"}
tags: ['Scaling Laws', 'Training Techniques', 'Efficiency and Optimization', 'Pretraining Methods']
---
Scaling large language models (LLMs) has driven significant advancements, yet it faces diminishing returns and escalating energy demands. This work introduces test-time compute (TTC)-allocating additional computational resources during inference-as a compelling complement to conventional scaling strategies. Specifically, we investigate whether employing TTC can achieve superior accuracy-energy trade-offs compared to simply increasing model size. Our empirical analysis reveals that TTC surpasses traditional model scaling in accuracy/energy efficiency, with notable gains in tasks demanding complex reasoning rather than mere factual recall. Further, we identify a critical interaction between TTC performance and output sequence length, demonstrating that strategically adjusting compute resources at inference time according to query complexity can substantially enhance efficiency. Our findings advocate for TTC as a promising direction, enabling more sustainable, accurate, and adaptable deployment of future language models without incurring additional pretraining costs.

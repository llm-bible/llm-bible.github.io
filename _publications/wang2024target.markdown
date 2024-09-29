---
layout: publication
title: Target-constrained Bidirectional Planning For Generation Of Target-oriented Proactive Dialogue
authors: Wang Jian, Lin Dongding, Li Wenjie
conference: "Arxiv"
year: 2024
bibkey: wang2024target
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.06063"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Transformer']
---
Target-oriented proactive dialogue systems aim to lead conversations from a dialogue context toward a pre-determined target such as making recommendations on designated items or introducing new specific topics. To this end it is critical for such dialogue systems to plan reasonable actions to drive the conversation proactively and meanwhile to plan appropriate topics to move the conversation forward to the target topic smoothly. In this work we mainly focus on effective dialogue planning for target-oriented dialogue generation. Inspired by decision-making theories in cognitive science we propose a novel target-constrained bidirectional planning (TRIP) approach which plans an appropriate dialogue path by looking ahead and looking back. By formulating the planning as a generation task our TRIP bidirectionally generates a dialogue path consisting of a sequence of <action topic pairs using two Transformer decoders. They are expected to supervise each other and converge on consistent actions and topics by minimizing the decision gap and contrastive generation of targets. Moreover we propose a target-constrained decoding algorithm with a bidirectional agreement to better control the planning process. Subsequently we adopt the planned dialogue paths to guide dialogue generation in a pipeline manner where we explore two variants prompt-based generation and plan-controlled generation. Extensive experiments are conducted on two challenging dialogue datasets which are re-purposed for exploring target-oriented dialogue. Our automatic and human evaluations demonstrate that the proposed methods significantly outperform various baseline models.

---
layout: publication
title: 'VSTAR: Generative Temporal Nursing For Longer Dynamic Video Synthesis'
authors: Yumeng Li, William Beluch, Margret Keuper, Dan Zhang, Anna Khoreva
conference: "Arxiv"
year: 2024
bibkey: li2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13501"}
tags: ['RAG', 'Model Architecture', 'Merging', 'Attention Mechanism', 'Prompting']
---
Despite tremendous progress in the field of text-to-video (T2V) synthesis,
open-sourced T2V diffusion models struggle to generate longer videos with
dynamically varying and evolving content. They tend to synthesize quasi-static
videos, ignoring the necessary visual change-over-time implied in the text
prompt. At the same time, scaling these models to enable longer, more dynamic
video synthesis often remains computationally intractable. To address this
challenge, we introduce the concept of Generative Temporal Nursing (GTN), where
we aim to alter the generative process on the fly during inference to improve
control over the temporal dynamics and enable generation of longer videos. We
propose a method for GTN, dubbed VSTAR, which consists of two key ingredients:
1) Video Synopsis Prompting (VSP) - automatic generation of a video synopsis
based on the original single prompt leveraging LLMs, which gives accurate
textual guidance to different visual states of longer videos, and 2) Temporal
Attention Regularization (TAR) - a regularization technique to refine the
temporal attention units of the pre-trained T2V diffusion models, which enables
control over the video dynamics. We experimentally showcase the superiority of
the proposed approach in generating longer, visually appealing videos over
existing open-sourced T2V models. We additionally analyze the temporal
attention maps realized with and without VSTAR, demonstrating the importance of
applying our method to mitigate neglect of the desired visual change over time.

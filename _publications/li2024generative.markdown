---
layout: publication
title: VSTAR Generative Temporal Nursing For Longer Dynamic Video Synthesis
authors: Li Yumeng, Beluch William, Keuper Margret, Zhang Dan, Khoreva Anna
conference: "Arxiv"
year: 2024
bibkey: li2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.13501"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Prompting', 'RAG']
---
Despite tremendous progress in the field of text45;to45;video (T2V) synthesis open45;sourced T2V diffusion models struggle to generate longer videos with dynamically varying and evolving content. They tend to synthesize quasi45;static videos ignoring the necessary visual change45;over45;time implied in the text prompt. At the same time scaling these models to enable longer more dynamic video synthesis often remains computationally intractable. To address this challenge we introduce the concept of Generative Temporal Nursing (GTN) where we aim to alter the generative process on the fly during inference to improve control over the temporal dynamics and enable generation of longer videos. We propose a method for GTN dubbed VSTAR which consists of two key ingredients 1) Video Synopsis Prompting (VSP) 45; automatic generation of a video synopsis based on the original single prompt leveraging LLMs which gives accurate textual guidance to different visual states of longer videos and 2) Temporal Attention Regularization (TAR) 45; a regularization technique to refine the temporal attention units of the pre45;trained T2V diffusion models which enables control over the video dynamics. We experimentally showcase the superiority of the proposed approach in generating longer visually appealing videos over existing open45;sourced T2V models. We additionally analyze the temporal attention maps realized with and without VSTAR demonstrating the importance of applying our method to mitigate neglect of the desired visual change over time.

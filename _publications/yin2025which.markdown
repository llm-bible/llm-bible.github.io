---
layout: publication
title: 'Which Attention Heads Matter For In-context Learning?'
authors: Kayo Yin, Jacob Steinhardt
conference: "ICML 2025"
year: 2025
bibkey: yin2025which
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14010"}
tags: ['Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) exhibit impressive in-context learning (ICL)
capability, enabling them to perform new tasks using only a few demonstrations
in the prompt. Two different mechanisms have been proposed to explain ICL:
induction heads that find and copy relevant tokens, and function vector (FV)
heads whose activations compute a latent encoding of the ICL task. To better
understand which of the two distinct mechanisms drives ICL, we study and
compare induction heads and FV heads in 12 language models.
  Through detailed ablations, we discover that few-shot ICL performance depends
primarily on FV heads, especially in larger models. In addition, we uncover
that FV and induction heads are connected: many FV heads start as induction
heads during training before transitioning to the FV mechanism. This leads us
to speculate that induction facilitates learning the more complex FV mechanism
that ultimately drives ICL.

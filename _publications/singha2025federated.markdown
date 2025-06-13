---
layout: publication
title: 'Fedmvp: Federated Multi-modal Visual Prompt Tuning For Vision-language Models'
authors: Mainak Singha, Subhankar Roy, Sarthak Mehrotra, Ankit Jha, Moloud Abdar, Biplab Banerjee, Elisa Ricci
conference: "Arxiv"
year: 2025
bibkey: singha2025federated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20860"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Prompting', 'Attention Mechanism']
---
Textual prompt tuning adapts Vision-Language Models (e.g., CLIP) in federated
learning by tuning lightweight input tokens (or prompts) on local client data,
while keeping network weights frozen. Post training, only the prompts are
shared by the clients with the central server for aggregation. However, textual
prompt tuning often struggles with overfitting to known concepts and may be
overly reliant on memorized text features, limiting its adaptability to unseen
concepts. To address this limitation, we propose Federated Multimodal Visual
Prompt Tuning (FedMVP) that conditions the prompts on comprehensive contextual
information -- image-conditioned features and textual attribute features of a
class -- that is multimodal in nature. At the core of FedMVP is a PromptFormer
module that synergistically aligns textual and visual features through
cross-attention, enabling richer contexual integration. The dynamically
generated multimodal visual prompts are then input to the frozen vision encoder
of CLIP, and trained with a combination of CLIP similarity loss and a
consistency loss. Extensive evaluation on 20 datasets spanning three
generalization settings demonstrates that FedMVP not only preserves performance
on in-distribution classes and domains, but also displays higher
generalizability to unseen classes and domains when compared to
state-of-the-art methods. Codes will be released upon acceptance.

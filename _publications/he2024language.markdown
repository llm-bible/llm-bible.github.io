---
layout: publication
title: Language Models as Hierarchy Encoders
authors: He Yuan, Yuan Zhangdie, Chen Jiaoyan, Horrocks Ian
conference: "Arxiv"
year: 2024
bibkey: he2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.11374"}
tags: ['Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques', 'Transformer']
---
Interpreting hierarchical structures latent in language is a key limitation of current language models (LMs). While previous research has implicitly leveraged these hierarchies to enhance LMs approaches for their explicit encoding are yet to be explored. To address this we introduce a novel approach to re-train transformer encoder-based LMs as Hierarchy Transformer encoders (HiTs) harnessing the expansive nature of hyperbolic space. Our method situates the output embedding space of pre-trained LMs within a Poincare ball with a curvature that adapts to the embedding dimension followed by re-training on hyperbolic cluster and centripetal losses. These losses are designed to effectively cluster related entities (input as texts) and organise them hierarchically. We evaluate HiTs against pre-trained and fine-tuned LMs focusing on their capabilities in simulating transitive inference predicting subsumptions and transferring knowledge across hierarchies. The results demonstrate that HiTs consistently outperform both pre-trained and fine-tuned LMs in these tasks underscoring the effectiveness and transferability of our re-trained hierarchy encoders.

---
layout: publication
title: 'Think Before Recommend: Unleashing The Latent Reasoning Power For Sequential Recommendation'
authors: Jiakai Tang, Sunhao Dai, Teng Shi, Jun Xu, Xu Chen, Wen Chen, Wu Jian, Yuning Jiang
conference: "Arxiv"
year: 2025
bibkey: tang2025think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22675"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'RecSys', 'Pretraining Methods']
---
Sequential Recommendation (SeqRec) aims to predict the next item by capturing
sequential patterns from users' historical interactions, playing a crucial role
in many real-world recommender systems. However, existing approaches
predominantly adopt a direct forward computation paradigm, where the final
hidden state of the sequence encoder serves as the user representation. We
argue that this inference paradigm, due to its limited computational depth,
struggles to model the complex evolving nature of user preferences and lacks a
nuanced understanding of long-tail items, leading to suboptimal performance. To
address this issue, we propose \textbf\{ReaRec\}, the first inference-time
computing framework for recommender systems, which enhances user
representations through implicit multi-step reasoning. Specifically, ReaRec
autoregressively feeds the sequence's last hidden state into the sequential
recommender while incorporating special reasoning position embeddings to
decouple the original item encoding space from the multi-step reasoning space.
Moreover, we introduce two lightweight reasoning-based learning methods,
Ensemble Reasoning Learning (ERL) and Progressive Reasoning Learning (PRL), to
further effectively exploit ReaRec's reasoning potential. Extensive experiments
on five public real-world datasets and different SeqRec architectures
demonstrate the generality and effectiveness of our proposed ReaRec.
Remarkably, post-hoc analyses reveal that ReaRec significantly elevates the
performance ceiling of multiple sequential recommendation backbones by
approximately 30%-50%. Thus, we believe this work can open a new and
promising avenue for future research in inference-time computing for sequential
recommendation.

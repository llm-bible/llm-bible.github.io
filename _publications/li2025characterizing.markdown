---
layout: publication
title: 'Characterizing The Expressivity Of Transformer Language Models'
authors: Jiaoda Li, Ryan Cotterell
conference: "Arxiv"
year: 2025
bibkey: li2025characterizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23623"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Transformer-based language models (LMs) have achieved widespread empirical success, but their theoretical expressive power remains only partially understood. Prior work often relies on idealized models with assumptions -- such as arbitrary numerical precision and hard attention -- that diverge from real-world transformers. In this work, we provide an exact characterization of fixed-precision transformers with strict future masking and soft attention, an idealization that more closely mirrors practical implementations. We show that these models are precisely as expressive as a specific fragment of linear temporal logic that includes only a single temporal operator: the past operator. We further relate this logic to established classes in formal language theory, automata theory, and algebra, yielding a rich and unified theoretical framework for understanding transformer expressivity. Finally, we present empirical results that align closely with our theory: transformers trained on languages within their theoretical capacity generalize perfectly over lengths, while they consistently fail to generalize on languages beyond it.

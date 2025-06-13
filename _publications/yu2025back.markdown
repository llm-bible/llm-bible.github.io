---
layout: publication
title: 'Back Attention: Understanding And Enhancing Multi-hop Reasoning In Large Language Models'
authors: Zeping Yu, Yonatan Belinkov, Sophia Ananiadou
conference: "Arxiv"
year: 2025
bibkey: yu2025back
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10835'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'RAG', 'Model Architecture', 'Prompting', 'Pretraining Methods']
---
We investigate how large language models perform latent multi-hop reasoning
in prompts like "Wolfgang Amadeus Mozart's mother's spouse is". To analyze this
process, we introduce logit flow, an interpretability method that traces how
logits propagate across layers and positions toward the final prediction. Using
logit flow, we identify four distinct stages in single-hop knowledge
prediction: (A) entity subject enrichment, (B) entity attribute extraction, (C)
relation subject enrichment, and (D) relation attribute extraction. Extending
this analysis to multi-hop reasoning, we find that failures often stem from the
relation attribute extraction stage, where conflicting logits reduce prediction
accuracy. To address this, we propose back attention, a novel mechanism that
enables lower layers to leverage higher-layer hidden states from different
positions during attention computation. With back attention, a 1-layer
transformer achieves the performance of a 2-layer transformer. Applied to four
LLMs, back attention improves accuracy on five reasoning datasets,
demonstrating its effectiveness in enhancing latent multi-hop reasoning
ability.

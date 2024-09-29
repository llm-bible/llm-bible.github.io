---
layout: publication
title: "Resetox: Re-learning Attention Weights For Toxicity Mitigation In Machine Translation"
authors: Gilabert Javier García, Escolano Carlos, Costa-jussà Marta R.
conference: "Arxiv"
year: 2023
bibkey: gilabert2023re
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.11761"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Training Techniques', 'Transformer']
---
Our proposed method ReSeTOX (REdo SEarch if TOXic) addresses the issue of Neural Machine Translation (NMT) generating translation outputs that contain toxic words not present in the input. The objective is to mitigate the introduction of toxic language without the need for re-training. In the case of identified added toxicity during the inference process ReSeTOX dynamically adjusts the key-value self-attention weights and re-evaluates the beam search hypotheses. Experimental results demonstrate that ReSeTOX achieves a remarkable 5737; reduction in added toxicity while maintaining an average translation quality of 99.537; across 164 languages.

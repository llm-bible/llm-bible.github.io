---
layout: publication
title: 'Learnable Multi-scale Wavelet Transformer: A Novel Alternative To Self-attention'
authors: Andrew Kiruluta, Priscilla Burity, Samantha Williams
conference: "Arxiv"
year: 2025
bibkey: kiruluta2025learnable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08801'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Transformer', 'RAG', 'WMT', 'Training Techniques', 'Model Architecture', 'Tools', 'Applications', 'Pretraining Methods']
---
Transformer architectures, underpinned by the self-attention mechanism, have
achieved state-of-the-art results across numerous natural language processing
(NLP) tasks by effectively modeling long-range dependencies. However, the
computational complexity of self-attention, scaling quadratically with input
sequence length, presents significant challenges for processing very long
sequences or operating under resource constraints. This paper introduces the
Learnable Multi-Scale Wavelet Transformer (LMWT), a novel architecture that
replaces the standard dot-product self-attention with a learnable multi-scale
Haar wavelet transform module. Leveraging the intrinsic multi-resolution
properties of wavelets, the LMWT efficiently captures both local details and
global context. Crucially, the parameters of the wavelet transform, including
scale-specific coefficients, are learned end-to-end during training, allowing
the model to adapt its decomposition strategy to the data and task. We present
the detailed mathematical formulation of the learnable Haar wavelet module and
its integration into the transformer framework, supplemented by an
architectural diagram. We conduct a comprehensive experimental evaluation on a
standard machine translation benchmark (WMT16 En-De), comparing the LMWT
against a baseline self-attention transformer using metrics like BLEU score,
perplexity, and token accuracy. Furthermore, we analyze the computational
complexity, highlighting the linear scaling of our approach, discuss its
novelty in the context of related work, and explore the interpretability
offered by visualizing the learned Haar coefficients. Our results indicate that
the LMWT achieves competitive performance while offering substantial
computational advantages, positioning it as a promising and novel alternative
for efficient sequence modeling.

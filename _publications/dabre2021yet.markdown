---
layout: publication
title: YANMTT Yet Another Neural Machine Translation Toolkit
authors: Dabre Raj, Sumita Eiichiro
conference: "Arxiv"
year: 2021
bibkey: dabre2021yet
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.11126"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques', 'Transformer']
---
In this paper we present our open45;source neural machine translation (NMT) toolkit called Yet Another Neural Machine Translation Toolkit abbreviated as YANMTT which is built on top of the Transformers library. Despite the growing importance of sequence to sequence pre45;training there surprisingly few if not none well established toolkits that allow users to easily do pre45;training. Toolkits such as Fairseq which do allow pre45;training have very large codebases and thus they are not beginner friendly. With regards to transfer learning via fine45;tuning most toolkits do not explicitly allow the user to have control over what parts of the pre45;trained models can be transferred. YANMTT aims to address these issues via the minimum amount of code to pre45;train large scale NMT models selectively transfer pre45;trained parameters and fine45;tune them perform translation as well as extract representations and attentions for visualization and analyses. Apart from these core features our toolkit also provides other advanced functionalities such as but not limited to document/multi45;source NMT simultaneous NMT and model compression via distillation which we believe are relevant to the purpose behind our toolkit.

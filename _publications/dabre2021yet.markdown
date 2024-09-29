---
layout: publication
title: YANMTT&#58; Yet Another Neural Machine Translation Toolkit
authors: Dabre Raj, Sumita Eiichiro
conference: "Arxiv"
year: 2021
bibkey: dabre2021yet
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2108.11126"}
tags: ['Applications', 'Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Tools', 'Training Techniques', 'Transformer']
---
In this paper we present our open-source neural machine translation (NMT) toolkit called Yet Another Neural Machine Translation Toolkit abbreviated as YANMTT which is built on top of the Transformers library. Despite the growing importance of sequence to sequence pre-training there surprisingly few if not none well established toolkits that allow users to easily do pre-training. Toolkits such as Fairseq which do allow pre-training have very large codebases and thus they are not beginner friendly. With regards to transfer learning via fine-tuning most toolkits do not explicitly allow the user to have control over what parts of the pre-trained models can be transferred. YANMTT aims to address these issues via the minimum amount of code to pre-train large scale NMT models selectively transfer pre-trained parameters and fine-tune them perform translation as well as extract representations and attentions for visualization and analyses. Apart from these core features our toolkit also provides other advanced functionalities such as but not limited to document/multi-source NMT simultaneous NMT and model compression via distillation which we believe are relevant to the purpose behind our toolkit.

---
layout: publication
title: 'Building High-accuracy Multilingual ASR With Gated Language Experts And Curriculum Training'
authors: Eric Sun, Jinyu Li, Yuxuan Hu, Yimeng Zhu, Long Zhou, Jian Xue, Peidong Wang, Linquan Liu, Shujie Liu, Edward Lin, Yifan Gong
conference: "Arxiv"
year: 2023
bibkey: sun2023building
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2303.00786'}
tags: ['Transformer', 'ACL', 'RAG', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
We propose gated language experts and curriculum training to enhance
multilingual transformer transducer models without requiring language
identification (LID) input from users during inference. Our method incorporates
a gating mechanism and LID loss, enabling transformer experts to learn
language-specific information. By combining gated transformer experts with
shared transformer layers, we construct multilingual transformer blocks and
utilize linear experts to effectively regularize the joint network. The
curriculum training scheme leverages LID to guide the gated experts in
improving their respective language performance. Experimental results on a
bilingual task involving English and Spanish demonstrate significant
improvements, with average relative word error reductions of 12.5% and 7.3%
compared to the baseline bilingual and monolingual models, respectively.
Notably, our method achieves performance comparable to the upper-bound model
trained and inferred with oracle LID. Extending our approach to trilingual,
quadrilingual, and pentalingual models reveals similar advantages to those
observed in the bilingual models, highlighting its ease of extension to
multiple languages.

---
layout: publication
title: 'Exploring Compositional Generalization (in Recogs_pos) By Transformers Using Restricted Access Sequence Processing (RASP)'
authors: William Bruns
conference: "Arxiv"
year: 2025
bibkey: bruns2025exploring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.15349'}
tags: ['Attention Mechanism', 'Arxiv', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
Humans understand new combinations of words encountered if they are
combinations of words recognized from different contexts, an ability called
Compositional Generalization. The COGS benchmark (Kim and Linzen, 2020)
arXiv:2010.05465 reports 0% accuracy for Transformer models on some structural
generalizations. We use (Weiss et al., 2021) arXiv:2106.06981's Restricted
Access Sequence Processing (RASP), a Transformer-equivalent programming
language, to prove by construction that a Transformer encoder-decoder can
perform the semantically equivalent ReCOGS_pos (Wu et al., 2024)
arXiv:2303.13716 variant of COGS systematically and compositionally: Our RASP
model attains 100% semantic exact match on the ReCOGS test set and 100% SEM on
all generalization splits except obj_pp_to_subj_pp which gets 92%. Furthermore,
our RASP model shows the ReCOGS_pos task does not require a hierarchical or
tree-structured solution: we use word-level tokens with an "embedding" layer
that tags with possible parts of speech, applying just once per encoder pass 19
attention-head compatible flat pattern-matching rules, shown using grammar
coverage (Zeller et al., 2023) to be learnable from the training data, plus
general prepositional phrase (pp) handling and sentential complement (cp)
handling logic, and output the next logical form (LF) token (repeating until
the LF is complete). The model does not apply recursive, tree-structured rules
like 'np_det pp np -> np_pp -> np', but scores 100% semantic and string exact
match on pp recursion, cp recursion using the decoder loop.

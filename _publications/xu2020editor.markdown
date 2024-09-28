---
layout: publication
title: EDITOR an Edit-Based Transformer with Repositioning for Neural Machine Translation with Soft Lexical Constraints
authors: Xu Weijia, Carpuat Marine
conference: "Arxiv"
year: 2020
bibkey: xu2020editor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.06868"}
tags: ['ARXIV', 'Applications', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
We introduce an Edit-Based Transformer with Repositioning (EDITOR) which makes sequence generation flexible by seamlessly allowing users to specify preferences in output lexical choice. Building on recent models for non-autoregressive sequence generation (Gu et al. 2019) EDITOR generates new sequences by iteratively editing hypotheses. It relies on a novel reposition operation designed to disentangle lexical choice from word positioning decisions while enabling efficient oracles for imitation learning and parallel edits at decoding time. Empirically EDITOR uses soft lexical constraints more effectively than the Levenshtein Transformer (Gu et al. 2019) while speeding up decoding dramatically compared to constrained beam search (Post and Vilar 2018). EDITOR also achieves comparable or better translation quality with faster decoding speed than the Levenshtein Transformer on standard Romanian-English English-German and English-Japanese machine translation tasks.

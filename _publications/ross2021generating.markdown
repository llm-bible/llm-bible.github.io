---
layout: publication
title: 'Tailor: Generating And Perturbing Text With Semantic Controls'
authors: Ross Alexis, Wu Tongshuang, Peng Hao, Peters Matthew E., Gardner Matt
conference: "Arxiv"
year: 2021
bibkey: ross2021generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2107.07150"}
tags: ['Applications', 'Language Modeling', 'Training Techniques']
---
'Controlled text perturbation is useful for evaluating and improving model generalizability. However, current techniques rely on training a model for every target perturbation, which is expensive and hard to generalize. We present Tailor, a semantically-controlled text generation system. Tailor builds on a pretrained seq2seq model and produces textual outputs conditioned on control codes derived from semantic representations. We craft a set of operations to modify the control codes, which in turn steer generation towards targeted attributes. These operations can be further composed into higher-level ones, allowing for flexible perturbation strategies. We demonstrate the effectiveness of these perturbations in multiple applications. First, we use Tailor to automatically create high-quality contrast sets for four distinct natural language processing (NLP) tasks. These contrast sets contain fewer spurious artifacts and are complementary to manually annotated ones in their lexical diversity. Second, we show that Tailor perturbations can improve model generalization through data augmentation. Perturbing just 2&#37; of training data leads to a 5.8-point gain on an NLI challenge set measuring reliance on syntactic heuristics.'

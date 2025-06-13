---
layout: publication
title: 'Learning To Reason For Long-form Story Generation'
authors: Alexander Gurung, Mirella Lapata
conference: "Arxiv"
year: 2025
bibkey: gurung2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.22828'}
tags: ['Reinforcement Learning', 'Fine-Tuning', 'Prompting']
---
Generating high-quality stories spanning thousands of tokens requires
competency across a variety of skills, from tracking plot and character arcs to
keeping a consistent and engaging style. Due to the difficulty of sourcing
labeled datasets and precise quality measurements, most work using large
language models (LLMs) for long-form story generation uses combinations of
hand-designed prompting techniques to elicit author-like behavior. This is a
manual process that is highly dependent on the specific story-generation task.
Motivated by the recent success of applying RL with Verifiable Rewards to
domains like math and coding, we propose a general story-generation task
(Next-Chapter Prediction) and a reward formulation (Verified Rewards via
Completion Likelihood Improvement) that allows us to use an unlabeled book
dataset as a learning signal for reasoning. We learn to reason over a story's
condensed information and generate a detailed plan for the next chapter. Our
reasoning is evaluated via the chapters it helps a story-generator create, and
compared against non-trained and supervised finetuning (SFT) baselines.
Pairwise human judgments reveal the chapters our learned reasoning produces are
preferred across almost all metrics, and the effect is more pronounced in Scifi
and Fantasy genres.

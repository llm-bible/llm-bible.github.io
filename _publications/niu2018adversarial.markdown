---
layout: publication
title: Adversarial Over-sensitivity And Over-stability Strategies For Dialogue Models
authors: Tong Niu, Mohit Bansal
conference: Arxiv
year: 2018
citations: 23
bibkey: niu2018adversarial
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.02079'}]
tags: [Security, Tokenization]
---
We present two categories of model-agnostic adversarial strategies that
reveal the weaknesses of several generative, task-oriented dialogue models:
Should-Not-Change strategies that evaluate over-sensitivity to small and
semantics-preserving edits, as well as Should-Change strategies that test if a
model is over-stable against subtle yet semantics-changing modifications. We
next perform adversarial training with each strategy, employing a max-margin
approach for negative generative examples. This not only makes the target
dialogue model more robust to the adversarial inputs, but also helps it perform
significantly better on the original inputs. Moreover, training on all
strategies combined achieves further improvements, achieving a new
state-of-the-art performance on the original task (also verified via human
evaluation). In addition to adversarial training, we also address the
robustness task at the model-level, by feeding it subword units as both inputs
and outputs, and show that the resulting model is equally competitive, requires
only 1/4 of the original vocabulary size, and is robust to one of the
adversarial strategies (to which the original model is vulnerable) even without
adversarial training.
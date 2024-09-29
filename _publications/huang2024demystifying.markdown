---
layout: publication
title: Demystifying Verbatim Memorization In Large Language Models
authors: Huang Jing, Yang Diyi, Potts Christopher
conference: "Arxiv"
year: 2024
bibkey: huang2024demystifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17817"}
tags: ['Applications', 'Language Modeling', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) frequently memorize long sequences verbatim often with serious legal and privacy implications. Much prior work has studied such verbatim memorization using observational data. To complement such work we develop a framework to study verbatim memorization in a controlled setting by continuing pre45;training from Pythia checkpoints with injected sequences. We find that (1) non45;trivial amounts of repetition are necessary for verbatim memorization to happen; (2) later (and presumably better) checkpoints are more likely to verbatim memorize sequences even for out45;of45;distribution sequences; (3) the generation of memorized sequences is triggered by distributed model states that encode high45;level features and makes important use of general language modeling capabilities. Guided by these insights we develop stress tests to evaluate unlearning methods and find they often fail to remove the verbatim memorized information while also degrading the LM. Overall these findings challenge the hypothesis that verbatim memorization stems from specific model weights or mechanisms. Rather verbatim memorization is intertwined with the LMs general capabilities and thus will be very difficult to isolate and suppress without degrading model quality.

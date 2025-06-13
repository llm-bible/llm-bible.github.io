---
layout: publication
title: 'Memorization Or Interpolation ? Detecting LLM Memorization Through Input Perturbation Analysis'
authors: Albérick Euraste Djiré, Abdoul Kader Kaboré, Earl T. Barr, Jacques Klein, Tegawendé F. Bissyandé
conference: "Arxiv"
year: 2025
bibkey: djiré2025memorization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.03019"}
tags: ['Tools', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
While Large Language Models (LLMs) achieve remarkable performance through
training on massive datasets, they can exhibit concerning behaviors such as
verbatim reproduction of training data rather than true generalization. This
memorization phenomenon raises significant concerns about data privacy,
intellectual property rights, and the reliability of model evaluations. This
paper introduces PEARL, a novel approach for detecting memorization in LLMs.
PEARL assesses how sensitive an LLM's performance is to input perturbations,
enabling memorization detection without requiring access to the model's
internals. We investigate how input perturbations affect the consistency of
outputs, enabling us to distinguish between true generalization and
memorization. Our findings, following extensive experiments on the Pythia open
model, provide a robust framework for identifying when the model simply
regurgitates learned information. Applied on the GPT 4o models, the PEARL
framework not only identified cases of memorization of classic texts from the
Bible or common code from HumanEval but also demonstrated that it can provide
supporting evidence that some data, such as from the New York Times news
articles, were likely part of the training data of a given model.

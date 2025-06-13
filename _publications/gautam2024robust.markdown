---
layout: publication
title: 'Robust Pronoun Fidelity With English Llms: Are They Reasoning, Repeating, Or Just Biased?'
authors: Vagrant Gautam, Eileen Bingert, Dawei Zhu, Anne Lauscher, Dietrich Klakow
conference: "Arxiv"
year: 2024
bibkey: gautam2024robust
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.03134'}
tags: ['RAG', 'Security', 'Model Architecture', 'Reinforcement Learning', 'Ethics and Bias']
---
Robust, faithful and harm-free pronoun use for individuals is an important
goal for language model development as their use increases, but prior work
tends to study only one or two of these characteristics at a time. To measure
progress towards the combined goal, we introduce the task of pronoun fidelity:
given a context introducing a co-referring entity and pronoun, the task is to
reuse the correct pronoun later. We present RUFF, a carefully-designed dataset
of over 5 million instances to measure robust pronoun fidelity in English, and
we evaluate 37 model variants from nine popular families, across architectures
(encoder-only, decoder-only and encoder-decoder) and scales (11M-70B
parameters). When an individual is introduced with a pronoun, models can mostly
faithfully reuse this pronoun in the next sentence, but they are significantly
worse with she/her/her, singular they and neopronouns. Moreover, models are
easily distracted by non-adversarial sentences discussing other people; even
one sentence with a distractor pronoun causes accuracy to drop on average by 34
percentage points. Our results show that pronoun fidelity is not robust, in a
simple, naturalistic setting where humans achieve nearly 100% accuracy. We
encourage researchers to bridge the gaps we find and to carefully evaluate
reasoning in settings where superficial repetition might inflate perceptions of
model performance.

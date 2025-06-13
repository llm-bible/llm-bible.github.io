---
layout: publication
title: '"short-length" Adversarial Training Helps Llms Defend "long-length" Jailbreak Attacks: Theoretical And Empirical Evidence'
authors: Shaopeng Fu, Liang Ding, Di Wang
conference: "Arxiv"
year: 2025
bibkey: fu2025adversarial
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04204'}
  - {name: "Code", url: 'https://github.com/fshp971/adv-icl'}
tags: ['Has Code', 'Transformer', 'Security', 'Training Techniques', 'Model Architecture', 'Prompting', 'Pretraining Methods']
---
Jailbreak attacks against large language models (LLMs) aim to induce harmful
behaviors in LLMs through carefully crafted adversarial prompts. To mitigate
attacks, one way is to perform adversarial training (AT)-based alignment, i.e.,
training LLMs on some of the most adversarial prompts to help them learn how to
behave safely under attacks. During AT, the length of adversarial prompts plays
a critical role in the robustness of aligned LLMs. This paper focuses on
adversarial suffix jailbreak attacks and unveils that to defend against a
jailbreak attack with an adversarial suffix of length \\(\Theta(M)\\), it is enough
to align LLMs on prompts with adversarial suffixes of length
\\(\Theta(\sqrt\{M\})\\). Theoretically, we analyze the adversarial in-context
learning of linear transformers on linear regression tasks and prove a robust
generalization bound for trained transformers. The bound depends on the term
\\(\Theta(\sqrt\{M_\{\text\{test\}\}\}/M_\{\text\{train\}\})\\), where \\(M_\{\text\{train\}\}\\) and
\\(M_\{\text\{test\}\}\\) are the number of adversarially perturbed in-context samples
during training and testing. Empirically, we conduct AT on popular open-source
LLMs and evaluate their robustness against jailbreak attacks of different
adversarial suffix lengths. Results confirm a positive correlation between the
attack success rate and the ratio of the square root of the adversarial suffix
during jailbreaking to the length during AT. Our findings show that it is
practical to defend "long-length" jailbreak attacks via efficient
"short-length" AT. The code is available at https://github.com/fshp971/adv-icl.

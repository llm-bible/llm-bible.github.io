---
layout: publication
title: 'Towards Neural No-resource Language Translation: A Comparative Evaluation Of Approaches'
authors: Madhavendra Thakur
conference: "Arxiv"
year: 2024
bibkey: thakur2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20584"}
tags: ['Fine-Tuning', 'Applications', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
No-resource languages - those with minimal or no digital representation - pose unique challenges for machine translation (MT). Unlike low-resource languages, which rely on limited but existent corpora, no-resource languages often have fewer than 100 sentences available for training. This work explores the problem of no-resource translation through three distinct workflows: fine-tuning of translation-specific models, in-context learning with large language models (LLMs) using chain-of-reasoning prompting, and direct prompting without reasoning. Using Owens Valley Paiute as a case study, we demonstrate that no-resource translation demands fundamentally different approaches from low-resource scenarios, as traditional approaches to machine translation, such as those that work for low-resource languages, fail. Empirical results reveal that, although traditional approaches fail, the in-context learning capabilities of general-purpose large language models enable no-resource language translation that outperforms low-resource translation approaches and rivals human translations (BLEU 0.45-0.6); specifically, chain-of-reasoning prompting outperforms other methods for larger corpora, while direct prompting exhibits advantages in smaller datasets. As these approaches are language-agnostic, they have potential to be generalized to translation tasks from a wide variety of no-resource languages without expert input. These findings establish no-resource translation as a distinct paradigm requiring innovative solutions, providing practical and theoretical insights for language preservation.
